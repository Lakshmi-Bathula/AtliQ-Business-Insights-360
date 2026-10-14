# AtliQ-Business-Insights-360

Welcome to my Business Insights 360 Power BI Project.This repository showcases an interactive business intelligence solution developed to analyze AtliQ Hardware's performance across five key areas: Finance, Sales, Marketing, Supply Chain, and Executive.Using Power BI dashboards and data modeling, this project explores key business metrics such as Net Sales, Gross Margin, and Net Profit. It also helps analyze forecast accuracy, evaluate regional market share, identify business trends, and generate actionable insights to support data-driven decision-making and sustainable business growth

## Table of Contents

- [Introduction](#introduction)
- [Problem-statement](#problem-statement)
- [Data Sources](#data-sources)
- [Data Model](#data-model)
- [Usage](#usage)
- [Visual Insights](#visual-insights)
- [License](#license)

### Introduction

*Project Title:* Business Insights 360  
*Created By:* Lakshmi Bathula  
*Tools Used:* Excel, SQL, Power BI

*Focus Areas:* Integrated Business Intelligence, Financial Performance Analysis, and Supply Chain Optimization.

### Problem statement

**AtliQ Hardware** is a fast-growing electronics company based in India, with operations in multiple countries. Despite their rapid growth, they relied heavily on Excel for data analysis, which proved inefficient, error-prone, and incapable of generating actionable insights.

Due to the lack of effective analytics, the company suffered major losses in the Latin America region. To address this, the senior leadership initiated a business intelligence project to build insightful dashboards using Power BI for better strategic decisions.

###  Data Sources

#### 📁 SQL Databases

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

### Data Model 

- **Model Type:** Snowflake schema
- **Entity Relationship Diagram:**

  ![Entity Relationship Diagram](images/er-diagram.pn)

