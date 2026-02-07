# Sales Performance Analysis Dashboard (Power BI)

## Project Overview

This project presents a comprehensive **Sales Performance Analysis Dashboard** built using Power BI to analyze business performance across multiple dimensions such as sales, profit, customers, and promotions.

The dashboard helps stakeholders monitor trends, identify top and low-performing customers, evaluate promotional effectiveness, and compare performance across different time periods to support data-driven decision-making.

---

## Business Objectives

* Identify **Top and Bottom Customers** based on Net Sales, Profit, and Units Sold.
* Analyze the **relationship between Profit and Net Sales**.
* Track **Sales Trends over multiple years** to identify seasonality and growth.
* Evaluate the impact of **Promotion Categories and Discounts**.
* Compare **current performance with previous periods**.
* Enable dynamic filtering for detailed analysis by Date, Customer, Product, and Promotion.

---

## Dataset Description

The dataset contains transaction-level sales data including:

* Order ID
* Customer ID & Customer Name
* Product ID & Product Name
* Order Date
* Promotion Category
* Discount Percentage & Discount Value
* Net Sales
* Profit
* Units Sold

**Total Orders Analyzed:** 3510
**Time Period:** 2020 – 2024

---

## Data Preparation (Power Query)

* Cleaned and standardized data formats.
* Removed duplicate and null records.
* Converted columns to appropriate data types.
* Created derived fields:

  * Year, Month, Day
  * Profit calculations
  * Aggregated Net Sales
* Optimized dataset for efficient reporting.

---

## Data Model

* Structured transactional data for analysis.
* Built relationships between:

  * Customers
  * Products
  * Orders
  * Date fields
* Enabled time-based and hierarchical analysis.

---

## Dashboard Features

### 1. Sales Overview

* Total Orders KPI (3510)
* Sales Trend by Year (2020–2024)
* Profit vs Net Sales Scatter Plot
* Net Sales by City (Map Visualization)
* Average Discount by Promotion Category

---

### 2. Top / Bottom Analysis

* Top 5 Customers by:

  * Net Sales
  * Units Sold
  * Profit
* Bottom 5 Customers by the same metrics
  This helps identify high-value customers and low-performing segments.

---

### 3. Year-over-Year Comparison

* Dual Date Filters for period comparison
* KPI Cards for:

  * Total Sales
  * Total Profit
  * Total Quantity Sold
* Helps evaluate business growth across different time periods.

---

### 4. Interactive Filtering

Users can filter the entire dashboard by:

* Date
* Customer Name
* Product Name
* Promotion Name

A detailed table view shows filtered transaction-level data.

---

## Key Insights

* Strong positive correlation between **Profit and Net Sales**.
* Promotional campaigns significantly impact discount levels.
* Sales performance is concentrated among top customers.
* Seasonal trends observed across years.
* Year-over-year analysis helps track business growth.

---

## Tools & Technologies

* Power BI Desktop
* Power Query
* DAX (Data Analysis Expressions)
* Microsoft Excel (Data Source)


## Project Value

This dashboard helps organizations:

* Monitor sales performance
* Identify key customers
* Optimize promotional strategies
* Track profitability trends
* Make informed business decisions
