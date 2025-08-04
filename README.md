# Customer-Demographics-and-Spending-Patterns
# 💳 Mitron Bank: Customer Demographics and Spending Analysis Dashboard

## 📌 Overview

This repository contains an interactive Power BI dashboard developed as a **pilot project** for Mitron Bank, a legacy financial institution based in Hyderabad, India. The dashboard is designed to analyze customer demographics and spending behavior to support **strategic decisions for launching a new line of credit cards**.


---

## 🎯 Objective

To leverage customer data and provide actionable insights that help Mitron Bank:
- Understand customer demographics
- Analyze income utilization and spending patterns
- Identify high-value customer segments
- Strategically design and position new credit card offerings

---

## 🧠 Key Insights & Deliverables

### 1. **Customer Demographics**
- Gender distribution: **1403 Female**, **2597 Male**
- Highest customer concentration: **Age group 25–34**
- Major cities: **Mumbai, Delhi NCR, Bengaluru, Chennai, Hyderabad**
- Occupation: Most customers are **Salaried IT Employees**

### 2. **Utilisation of Income**
- Average Income: **$51.66K**
- Average Monthly Spend: **$22.12K**
- Overall Income Utilization: **42.82%**
- Highest utilization by: **Salaried IT Employees (51.04%)**

### 3. **Spending Trends & Insights**
- Top spend categories: **Bills, Electronics, Groceries**
- Payment Preference: **Credit Cards (40.74%)**
- Most used in: **Mumbai & Bengaluru**
- Age group **25–34** uses credit cards the most (**46.62%**)

### 4. **Top Customer Profiles**
- Top cities by income utilization: **Mumbai, Delhi NCR, Bengaluru**
- Top 3 occupations by credit card usage:  
  1. Salaried IT Employees  
  2. Salaried Other Employees  
  3. Government Employees

---

## 🧰 Dataset Information

### `dim_customers.csv`
Customer demographic information:
- `customer_id`
- `gender`, `age_group`, `marital_status`, `city`, `occupation`
- `average_income`

### `fact_spends.csv`
Spending data across categories and months:
- `customer_id`, `month`, `category`
- `payment_type`, `spends`

📄 See `meta_data.txt` for full schema.

---

## 📊 Tools Used

- **Power BI** for dashboard creation
- **Microsoft Bing Maps** integration for geospatial insights

---

## 📎 Files Included

- `1. Home_Page.png` – Dashboard Navigation
- `2. Demographic Classificatiion.png` – Customer Overview
- `3. Income Utilization.png` – Income vs Spend Analysis
- `4. Spending Insight.png` – Payment Behavior & Spend Types
- `5. Key Customer Segments.png` – High Value Segment Insights
- `meta_data.txt` – Dataset column metadata
- `problem_statement.pdf` – Project brief and challenge description

---
