# 📈 Sales Forecasting Dashboard using Linear Regression

An end-to-end **sales analytics and forecasting project** built with Python. It prepares sales data, explores revenue patterns across products, categories, and regions, and uses **Linear Regression** to forecast revenue for the next 6 months.

---

## 📌 Project Overview

Accurate sales forecasts help businesses plan inventory, set budgets, and time marketing campaigns. This project analyzes **24 months of sales data (Jan 2023 – Dec 2024)** across 5 products and 4 categories, identifies trends and seasonality, and projects future revenue.

---

## 🎯 Objectives

- Prepare and engineer features from raw sales data
- Analyze revenue and profit by product, category, and region
- Study the relationship between ad spend and revenue
- Identify seasonal patterns in units sold
- Build a regression model to forecast the next 6 months of revenue
- Evaluate the model with R² and MAE

---

## 🔄 Workflow

### Step 1: Data Preparation & Feature Engineering
- Parsed dates and handled missing values using the **median**
- Created time features: `Month`, `Year`, `MonthNum`
- Calculated **Profit** = Revenue − Ad Spend
- Saved the processed data as `sales_clean.csv`

### Step 2: Data Visualization
Six charts built with Matplotlib and Seaborn:
1. Total monthly revenue trend
2. Total revenue by product
3. Revenue by category (pie) and region (bar)
4. Ad spend vs revenue (scatter, by category)
5. Monthly profit by product
6. Heatmap of average units sold by product and month

### Step 3: Sales Forecasting (Linear Regression)
- Aggregated total monthly revenue
- Trained a **Linear Regression** model using `MonthNum` as the feature
- Evaluated with **R² Score** and **Mean Absolute Error (MAE)**
- Generated a **6-month revenue forecast**
- Visualized actual vs predicted revenue and the forecast period

---

## 📦 Dataset

| Column | Description |
|---|---|
| Date | Month of sale |
| Product | Laptop Pro, Smart Watch, Office Chair, Running Shoes,
