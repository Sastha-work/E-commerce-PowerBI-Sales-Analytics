# Walmart E-Commerce Sales Analytics Dashboard

An interactive E-Commerce Sales Analytics Dashboard built using Microsoft Power BI to analyze sales performance, profitability, customer behavior, product performance, and store-level trends.

## Project Overview

This project analyzes a Walmart E-Commerce sales dataset containing 1 million transactions across multiple products, customers, stores, categories, brands, and regions.

The dashboard was designed to transform raw transactional data into meaningful business insights using Power BI.

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Data Visualization

## Dataset

- 1,000,000 transactions
- 30 columns
- 289K+ customers
- 89K+ products
- 30 stores
- 16 states
- 10 categories
- 20 brands
- Date range: January 2023 – December 2025

## Dashboard Pages

### 1. Executive Overview
Provides a high-level view of overall business performance including:

- Total Revenue
- Total Profit
- Total Orders
- Total Customers
- Total Quantity
- Profit Margin
- Revenue & Profit Trends
- Category Performance
- Sales by State
- Top Stores
- Payment Methods
- Customer Demographics

### 2. Sales Analysis
Focuses on revenue and profitability trends:

- Revenue & Profit Trends
- Sales by Category
- Sales by Payment Method
- Profit by Category
- Average Order Value
- Profit Margin
- Monthly Sales Performance

### 3. Customer Analytics
Analyzes customer behavior and demographics:

- Total Customers
- New Customers
- Repeat Customers
- Repeat Customer Rate
- Customer Age Groups
- Customer Gender
- Walmart+ Membership
- Customers by Region
- Top Customers

### 4. Product Analysis
Analyzes product and brand performance:

- Total Products
- Top Product by Quantity
- Lowest Selling Product
- Top Performing Brand
- Sales by Category
- Top Products by Sales
- Sales by Brand
- Profit by Product
- Order Status

### 5. Store & Geography
Provides geographical and store-level analysis:

- Sales by State
- Sales by City
- Sales by Region
- Top States by Sales
- Top Stores by Revenue

## Key Business Metrics

| Metric | Value |
|---|---:|
| Total Revenue | $127.80M |
| Total Profit | $18.94M |
| Profit Margin | 14.82% |
| Total Orders | 1M |
| Total Customers | 289K |
| Total Quantity | 2M |
| Average Order Value | $127.80 |

## Data Preparation

The dataset was cleaned and transformed using Power Query.

Key preparation steps included:

- Data type validation
- Data quality checks
- Brand data correction
- Creation of a corrected brand mapping
- Date table creation
- Relationship building
- Data modeling
- DAX measure development

## DAX Measures

Key measures developed for the dashboard include:

- Total Revenue
- Total Profit
- Total Orders
- Total Customers
- Total Quantity
- Average Order Value
- Profit Margin %
- Previous Month Revenue
- Previous Month Profit
- Previous Month Orders
- Previous Month Customers
- YoY Growth %
- YTD Revenue
- Repeat Customer Rate

## Dashboard Screenshots

Screenshots of the dashboard are available in the `Screenshots` folder.

## Project Structure

```text
E-commerce-PowerBI-Sales-Analytics/
│
├── README.md
│
├── PowerBI/
│   └── Walmart_Sales_Analytics.pbix
│
├── Screenshots/
│   ├── executive-overview.png
│   ├── sales-analysis.png
│   ├── customer-analytics.png
│   ├── product-analysis.png
│   └── store-geography.png
│
└── Dataset/
    └── walmart_sales_dataset.csv
