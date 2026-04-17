# 📊 Business Requirements Document (BRD)

## Sales & Customer Analytics Dashboard (Power BI)

---

## 1. 📌 Project Overview

This project delivers an interactive Power BI dashboard built on top of a SQL-based Data Warehouse (Gold Layer).

It enables stakeholders to analyze:
- Sales performance over time  
- Customer behavior and segmentation  
- Product performance  

The goal is to transform structured data into actionable business insights.

---

## 2. 🎯 Objectives

- Monitor key KPIs (Sales, Orders, Customers, Quantity)
- Analyze sales trends over time
- Identify top and underperforming products
- Understand customer distribution and segmentation
- Enable interactive filtering and exploration

---

## 3. 🗂️ Data Source

Data is sourced from the Gold Layer of the Data Warehouse:

- gold.fact_sales → transactional sales data  
- gold.dim_customers → customer details  
- gold.dim_products → product information  

Data is cleaned and ready for analytics.

---

## 4. 👥 Stakeholders

- Business Analysts  
- Sales Managers  
- Product Managers  
- Executives  

---

## 5. 📊 Dashboard Pages & Requirements

---

### 5.1 Executive Overview

**Purpose:** Provide a high-level summary of business performance  

**Visuals:**
- KPI Cards:
  - Total Sales (~29M)
  - Total Orders (~28K)
  - Total Customers (~18K)
  - Total Quantity (~60K)
- Sales Trend (monthly)
- Sales by Category
- Customer Segmentation (New, Regular, VIP)
- Top 10 Products by Sales
- Bottom 10 Products by Sales

---

### 5.2 Sales Performance

**Purpose:** Analyze sales trends and revenue patterns  

**Visuals:**
- Monthly Sales Trend
- Running/Cumulative Sales
- Revenue Contribution by Category (%)

---

### 5.3 Customer Insights

**Purpose:** Understand customer distribution and behavior  

**Visuals:**
- Customers by Country
- Customer Segmentation (Donut Chart)
- Customer-level sales table

---

### 5.4 Product Performance

**Purpose:** Evaluate product-level performance  

**Visuals:**
- Scatter Plot (Sales vs Quantity)
  - Colored by Product Performance (High, Mid, Low)
- Top 10 Products
- Bottom 10 Products

---

## 6. 🎛️ Filters & Interactivity

The dashboard includes global filters:

- Date Range  
- Country  
- Category  

All visuals support cross-filtering.

---

## 7. 📈 Key Metrics (KPIs)

- Total Sales  
- Total Orders  
- Total Customers  
- Total Quantity  
- Sales Contribution (%)  
- Running Sales  

---

## 8. 🧠 Data Model

The dashboard follows a star schema:

- Fact Table:
  - fact_sales  

- Dimension Tables:
  - dim_customers  
  - dim_products  

**Relationships:**
- fact_sales → dim_customers (customer_key)  
- fact_sales → dim_products (product_key)

---

## 9. ⚙️ Tools & Technologies

- SQL Server  
- Power BI  
- Microsoft Fabric  

---

## 10. 🚀 Expected Outcomes

- Clear visibility into business performance  
- Identification of key revenue drivers  
- Understanding of customer segments  
- Product performance evaluation  
- Interactive decision-making support  

---

## 11. 📌 Success Criteria

- Dashboard reflects accurate KPIs  
- Visuals respond to filters correctly  
- Insights are clear and actionable  
- Layout is user-friendly and intuitive  

---

## 12. 🔗 Project Context

This dashboard is part of an end-to-end analytics pipeline:

Data Warehouse → SQL Analysis → Power BI Dashboard
