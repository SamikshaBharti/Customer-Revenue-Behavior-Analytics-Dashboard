# Customer Revenue & Behavior Analytics Dashboard

## Overview
This project analyzes e-commerce customer data to understand revenue patterns, customer behavior, and satisfaction levels.  
The goal is to transform raw transactional data into meaningful business insights that can help teams make data-driven decisions.

The project follows an end-to-end analytics workflow using Python EDA, SQL, and Power BI, similar to how analytics is applied in real product-based companies.

## Problem Statement
E-commerce businesses often have large volumes of customer data but lack clear visibility into:
- Which customer segments drive the most revenue
- Which product categories perform best
- How discounts affect revenue and customer satisfaction
- Whether subscribed customers behave differently from non-subscribers

This project addresses these questions through structured analysis and visualization.

## Tools & Technologies
- **Python (Pandas, NumPy)** – Data cleaning and feature engineering  
- **SQL (PostgreSQL)** – Data storage and analytical queries  
- **Power BI** – Interactive dashboard and visualization  


## Project Workflow

### 1. Data Cleaning & Feature Engineering (Python)
- Cleaned raw customer data and handled missing values
- Standardized column names for consistency
- Created derived features such as:
  - Age groups
  - Purchase frequency
  - Customer satisfaction indicators based on review ratings
- Prepared an analytics-ready dataset for analysis

### 2. Data Analysis (SQL)
- Loaded cleaned data into PostgreSQL
- Wrote SQL queries to analyze:
  - Revenue and order volume by category
  - Customer segmentation by age group
  - Discount impact on purchases
  - Subscription-based spending behavior

### 3. Visualization (Power BI)
- Built an executive-level Power BI dashboard
- Added KPI cards for a quick business overview
- Created interactive charts and slicers to explore:
  - Category performance
  - Customer segments
  - Discount and subscription impact
- Designed the dashboard to support business decision-making

---

## Key Metrics
- Total Revenue  
- Total Customers  
- Average Order Value (AOV)  
- Low Review Rate (%)  
- Revenue and Order Contribution by Category  
- Customer Segmentation by Age Group and Subscription Status  

---

## Key Insights
- Young Adult customers contribute the highest share of total revenue, making them the most valuable segment.
- Clothing generates the highest revenue and order volume, followed by Accessories.
- Orders placed with discounts show a higher low-review rate, indicating potential customer dissatisfaction.
- Subscribed customers have a higher average order value, reflecting stronger engagement and retention.

---

## Dashboard
The Power BI dashboard provides a clear and interactive view of customer behavior and revenue performance.  
Users can filter data by category, age group, subscription status, discount usage, and shipping type to explore insights in detail.

---
![Customer Revenue Dashboard](C:\Users\HP\OneDrive\Pictures\Screenshots\Screenshot 2026-01-16 123011.png)
