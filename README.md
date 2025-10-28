# 📊 SQL Data Analysis Project

This project focuses on performing **end-to-end data analysis using SQL**, turning raw datasets into meaningful business insights.  
It demonstrates how structured queries, analytical functions, and performance reporting can help uncover sales trends, customer behavior, and product performance — all using pure SQL.

---

## 🎯 Project Objective

The goal of this project is to explore and analyze sales data to answer key business questions such as:
- How are sales performing over time?
- Which products and categories generate the highest revenue?
- Who are the top-performing customers?
- What are the key trends in customer and product performance year-over-year?

This project showcases how **SQL alone** can be used to perform **data cleaning, transformation, aggregation, and advanced analytics** — without external BI tools.

---

## 🧩 Project Highlights

### 🔹 1. Data Setup
- Created tables for:
  - `dim_customers`
  - `dim_products`
  - `fact_sales`
- Loaded CSV data using `BULK INSERT` statements.

### 🔹 2. Sales Performance Analysis
- Analyzed sales performance across **months and years** using:
  - `GROUP BY`, `DATETRUNC()`, and `FORMAT()`
- Metrics calculated:
  - Total Sales  
  - Total Customers  
  - Total Quantity Sold  

### 🔹 3. Cumulative & Growth Analysis
- Used **window functions** like `SUM() OVER()` and `AVG() OVER()` to compute:
  - Running Total of Sales  
  - Moving Average of Prices  

### 🔹 4. Year-over-Year (YoY) and Trend Analysis
- Implemented `LAG()` to compare current year’s sales with previous year.
- Segmented products as **Above Average**, **Below Average**, or **Stable** performers.

### 🔹 5. Customer Segmentation
- Classified customers based on spending and order history:
  - **VIP** – Spent > 5000 and active for > 12 months  
  - **Regular** – Spent ≤ 5000 and active for > 12 months  
  - **New** – Active for < 12 months

### 🔹 6. Product Insights
- Identified cost-based product segments:
  - Below 100, 100–500, 500–1000, Above 1000
- Measured contribution of each category to overall sales.

### 🔹 7. Analytical Reports
Created **views** for reusable insights:
- `report_customers` → Customer performance KPIs (Recency, Lifespan, Avg Spend)
- `report_products` → Product performance metrics (Revenue, Lifespan, Recency)

---

## 🧠 Key Learnings
- Gained hands-on experience with **SQL analytical functions** (`LAG()`, `OVER()`, `CASE`, `AVG()`, `SUM()`).
- Built **dynamic reports** using SQL views.
- Practiced **real-world data analysis** tasks like trend detection, segmentation, and KPI design.
- Strengthened understanding of **data relationships** (customers, products, and sales).

---

## ⚙️ Tools & Technologies
- **Microsoft SQL Server / T-SQL**
- **CSV Data Files**
- **SQL Analytical Queries**
- **Window Functions, CTEs, Joins, and Aggregations**

---

## 📈 Example KPIs Generated
| Metric | Description |
|--------|--------------|
| Total Sales | Sum of sales amount by time period |
| Average Order Value | Total sales / Total orders |
| Recency | Months since last order |
| Lifespan | Duration of customer activity |
| Customer Segmentation | VIP / Regular / New |
| Product Segmentation | High / Mid / Low Performer |

---

## 🌟 Author
**Amit Mishra**  
📊 Aspiring Data Analyst | SQL Enthusiast | BI Learner  
🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/amitmishra29/)  

---
