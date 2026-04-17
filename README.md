# 📊 Sales & Customer Analytics Dashboard (Power BI)

## 🚀 Project Overview

This project presents an interactive **Power BI dashboard** built on top of a structured **SQL Data Warehouse (Gold Layer)**.

It provides business insights into:
- Sales performance  
- Customer behavior  
- Product performance  

This project is part of an **end-to-end analytics pipeline**, transforming raw data into actionable insights.

---

## 🧱 Data Source

The dashboard uses the **Gold Layer** from my Data Warehouse project:

🔗 https://github.com/amitsinghanalyst/sql-data-warehouse-project

Tables used:
- `gold.fact_sales`  
- `gold.dim_customers`  
- `gold.dim_products`  

---

## 🎯 Objectives

- Monitor key KPIs (Sales, Orders, Customers, Quantity)
- Analyze trends over time  
- Identify top and underperforming products  
- Understand customer segmentation  
- Enable interactive data exploration  

---

## 📊 Dashboard Pages

### 1️⃣ Executive Overview
- KPI Cards (Sales, Orders, Customers, Quantity)
- Sales Trend  
- Sales by Category  
- Customer Segmentation  
- Top & Bottom Products  

---

### 2️⃣ Sales Performance
- Monthly Sales Trend  
- Running (Cumulative) Sales  
- Revenue Contribution by Category (%)  

---

### 3️⃣ Customer Insights
- Customers by Country  
- Customer Segmentation  
- Customer Sales Table  

---

### 4️⃣ Product Performance
- Sales vs Quantity (Scatter Plot)  
- Product Segmentation (High / Mid / Low)  
- Top & Bottom Products  

---

## 🧠 Key Insights

- Bikes category contributes the majority of total revenue  
- Sales show a consistent upward trend over time  
- A small group of products drives most of the revenue (Pareto effect)  
- Majority of customers are new, indicating growth opportunity  
- High-performing products generate strong revenue with moderate quantity  

---

## 🛠 Tools & Technologies

- SQL Server  
- Power BI  
- Microsoft Fabric  

---

## 🔗 Live Dashboard

👉 [View Interactive Dashboard](https://app.powerbi.com/reportEmbed?reportId=cfb0e14a-f06f-4213-8454-1a70cbd9475d&autoAuth=true&ctid=3edd1670-a7c7-409a-93d4-b5317ea16001)

---

## 📌 Project Flow

Data Warehouse → SQL Analysis → Power BI Dashboard

---

## ⭐ Conclusion

This project demonstrates an end-to-end data analytics workflow, combining data engineering, SQL analysis, and business intelligence to deliver actionable insights.
