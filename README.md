# Superstore Sales & Profit Analysis

## Project Overview

This project analyzes Superstore sales and profit data using Python, Pandas, and Power BI.

The goal is to identify sales and profit trends, category and regional performance, product and customer performance, state-level profitability, and shipping-day patterns.

## Objective

To analyze Superstore sales data and identify profitable areas, loss-making areas, important trends, and business opportunities that can support better decision-making.

## Tools & Technologies

- Python
- Pandas
- Google Colab
- Power BI Desktop
- CSV

## Project Workflow

Raw Superstore Data  
↓  
Python / Pandas  
↓  
Data Cleaning & Preparation  
↓  
Analytical Datasets  
↓  
Power BI  
↓  
Two-Page Dashboard  
↓  
Business Insights & Recommendations

## Dashboard

### Page 1 — Executive Summary

The first dashboard page provides an overview of:

- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Total Products
- Overall Profit Margin
- Sales & Profit by Year
- Sales & Profit by Category
- Sales & Profit by Region
- Top 5 Sub-Categories by Profit
- Bottom 5 Sub-Categories by Profit
- Sales & Profit by Shipping Days

### Page 2 — Product & Customer Analysis

The second page focuses on:

- Top 5 Customers by Profit
- Top 5 Customers by Sales
- Top 5 Products by Profit
- Bottom 5 Products by Profit
- Top 10 States by Profit
- Bottom 10 States by Profit

## Key Findings

- Sales and profit increased overall from 2014 to 2017.
- 2017 recorded the strongest overall sales and profit performance.
- Technology was the leading category in terms of sales.
- West was the highest-sales region.
- Copiers was the most profitable sub-category.
- Tables was the lowest-performing sub-category by profit and generated a significant loss.
- Product-level analysis identified both highly profitable and loss-making products.
- The Canon imageCLASS 2200 Advanced Copier was the highest-profit product in the analysis.
- The shipping-day analysis showed that 2 shipping days had the highest performance in the dashboard.

## Business Recommendations

- Investigate the reasons for losses in the Tables sub-category.
- Review pricing, discount levels, product costs, and shipping costs for loss-making products.
- Focus on consistently profitable products and identify opportunities to increase their sales.
- Review whether high discounts are reducing profit margins.
- Study the factors behind Technology's strong sales performance.
- Analyze the reasons for the West region's strong performance.
- Investigate the relationship between shipping duration, sales, and profitability.

## Project Structure

```text
Project 2 - Superstore Sales & Profit Analysis
│
├── README.md
│
├── 01_Data
│   ├── superstore_cleaned.csv
│   ├── dashboard_subcategory.csv
│   ├── dashboard_product.csv
│   └── dashboard_customer.csv
│
├── 02_PowerBI
│   ├── Superstore_Sales_Profit_Analysis.pbix
│   └── Superstore_Sales_Profit_Analysis.pdf
│
├── 03_Documentation
│   ├── Project_2_Summary.docx
│   └── Project_2_Python_Code_Learning_Guide.docx
│
└── 04_Python
    └── Project_2_Superstore_Analysis.ipynb
