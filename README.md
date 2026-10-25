# AtliQ-Business-Insights-360

Welcome to my Business Insights 360 Power BI Project.This repository showcases an interactive business intelligence solution developed to analyze AtliQ Hardware's performance across five key areas: Finance, Sales, Marketing, Supply Chain, and Executive.Using Power BI dashboards and data modeling, this project explores key business metrics such as Net Sales, Gross Margin, and Net Profit. It also helps analyze forecast accuracy, evaluate regional market share, identify business trends, and generate actionable insights to support data-driven decision-making and sustainable business growth

---

<h2>🚀 Introduction</h2>
<hr style="margin: 5px 0 10px 0;">

*Project Title:* Business Insights 360  
*Created By:* Lakshmi Bathula  
*Tools Used:* Excel, SQL, Power BI

*Focus Areas:* Integrated Business Intelligence, Financial Performance Analysis, and Supply Chain Optimization.

---
## 📌 Problem Statement

**AtliQ Hardware** is a fast-growing electronics company based in India, with operations in multiple countries. Despite their rapid growth, they relied heavily on Excel for data analysis, which proved inefficient, error-prone, and incapable of generating actionable insights.

Due to the lack of effective analytics, the company suffered major losses in the Latin America region. To address this, the senior leadership initiated a business intelligence project to build insightful dashboards using Power BI for better strategic decisions.

---

## 🛠️ Technologies Used

* **SQL** – For data extraction and transformation
* **Excel** – For additional datasets like market targets and shares
* **Power BI** – For report and dashboard development
* **DAX Language** – For data modeling and calculations
* **DAX Studio** – For performance tuning and optimization

---


<h2>💾 Data Sources</h2>
<hr style="margin: 5px 0 10px 0;">

### 📁 SQL Databases

**gdb041**

- `dim_customer` – Customer details
- `dim_market` – Market and country-level info
- `dim_product` – Product details
- `fact_sales_monthly` – Monthly sales quantity
- `fact_forecast_monthly` – Monthly forecasted quantity

**gdb056**

- `freight_cost` – Freight and other logistics costs
- `gross_price` – Gross price by product
- `manufacturing_cost` – Product manufacturing costs
- `pre_invoice_deductions` – Discounts before invoice
- `post_invoice_deductions` – Post-invoice and other discounts
  
### 🔗 📁 Excel Workbooks

- `targets` – Contains net sales, gross margin, and net profit targets by market
- `marketshare` – Contains AtliQ's and competitors' market share data
---

## 🧩 Data Model


- **Model Type:** Snowflake schema
- **Entity Relationship Diagram:**
![AtliQ Business Insights 360 Data Model](Data%20Model.png)
---
## 📊 Dashboards Overview

All dashboards are built within Power BI and navigated via a centralized **Home View**.

### 1. 🏠 Home View

Navigation panel for different views with interactive buttons:

- Finance View
- Sales View
- Marketing View
- Supply Chain View
- Executive View
- Information
- Support

![Home View Dashboard](./Home%20View.gif)

---
### 2. 💰 Finance View

* Full profit and loss statement
* Track performance over time across customers, products, and markets
* Designed to support financial analysis

![Finance View Dashboard](./Finance%20View.gif)

---
### 3. 📈 Sales View

* Key metrics: Net Sales, Gross Margin, Gross Margin %
* Evaluate customer performance

![Sales View Dashboard](./sales%20View.gif)

---
### 4. 🎯 Marketing View

* Key metrics: Net Sales, Gross Margin %, Net Profit, Net Profit %
* Focuses on product-level performance

![Marketing View Dashboard](./Marketing%20View.gif)

---
### 5. 🚚 Supply Chain View

* Forecast accuracy and net errors
* Customer- and product-wise analysis against last year
* Helps identify gaps in planning and delivery

![Supply Chain View Dashboard](./Supply%20Chain%20View.gif)

---
### 6. 🧑‍💼 Executive View

* Consolidated key performance indicators (KPIs)
* Market share insights
* Provides a high-level overview to support strategic decision-making

![Executive View Dashboard](./Executive%20View.gif)

---
<h2 style="margin-bottom: 5px;">✅ Project Outcome</h2>

* Created an interactive Power BI dashboard to analyze business performance.
* Combined business data into one dashboard for easy analysis.
* Analyzed sales, profit, and financial performance.
* Evaluated customer and product performance.
* Monitored forecast accuracy and identified supply chain issues.
* Identified areas for improvement across different departments.
* Helped stakeholders make better data-driven business decisions.
---
## 🎓 Skills Learned

### 💻 Technical Skills

* Power BI report development and publishing
* DAX measures and calculated columns
* SQL data extraction and transformation
* Data modeling using star and snowflake schemas
* Dashboard development using interactive visuals, bookmarks, and drill-through
* Power Query for data cleaning and transformation
* Performance optimization in Power BI

### 🤝 Soft Skills

* Understanding business requirements and defining KPIs
* Presenting insights through data storytelling
* Project planning and execution
* Version control using Git and GitHub
* Communicating technical insights clearly to non-technical stakeholders
---
## 📊 Visual Insights

**Live Dashboard:** https://tinyurl.com/37b6zu64

**Video Presentation:** https://youtu.be/2Mn7Z2t9xfU


