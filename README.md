# Walmart Retail Sales & Profitability Dashboard

Python and Power BI analysis of Walmart retail sales, profitability, transactions, and business performance.

## Project Overview

This project analyzes Walmart retail sales and profitability using Python, Pandas, and Power BI. The objective was to understand sales performance and profitability across different branches, cities, product categories, payment methods, and time periods.
The project covers the complete process from data cleaning and feature engineering to business analysis and interactive dashboard creation.

## Data Cleaning & Preparation

The original dataset contained 10,051 transaction records.

Using Python and Pandas, I performed the following data cleaning steps:

- Checked and removed 51 duplicate records.
- Identified 31 records with missing values in Unit Price and Quantity.
- Removed these records because both fields were required to calculate total sales.
- Converted Unit Price from text format to numeric format after removing the dollar sign.
- Converted the Date column into a proper datetime format.
- After cleaning, the dataset contained 9,969 valid transactions.

## Feature Engineering

After cleaning the data, I created additional features to support the analysis:

- Created Total Sales by multiplying Unit Price by Quantity.
- Calculated Profit by multiplying Total Sales by Profit Margin.
- Extracted Day Name, Month Name, and Year from the transaction date.
- Created a Shift column based on transaction time and categorized transactions into Morning, Afternoon, and Evening.

## Dashboard & KPIs

After completing the data preparation, the cleaned dataset was imported into Power BI to create an interactive sales and profitability dashboard.

The dashboard includes four key performance indicators:

- **Total Revenue:** Approximately 1.21M
- **Total Profit:** Approximately 476.14K
- **Total Transactions:** 9,969
- **Average Rating:** 5.83

The dashboard also includes interactive Year and Category slicers for exploring the data across different periods and product categories.

## Analysis & Visuals

The Power BI dashboard was designed to analyze sales and profitability from multiple business perspectives:

- Revenue by Branch to compare sales performance across locations.
- Revenue by Category to identify major revenue-generating product categories.
- Profit by Category to understand category-level profit contribution.
- Payment Method Distribution to analyze customer payment preferences.
- Monthly Revenue Trend to identify changes in revenue over time.
- Year and Category slicers to enable interactive analysis.

## Key Insights

- Fashion Accessories and Home & Lifestyle were among the stronger revenue-generating categories.
- Credit Card and E-wallet were the most commonly used payment methods.
- Revenue varied across different branches, highlighting differences in location-level sales performance.
- Profitability analysis provided additional insight beyond revenue by showing the contribution of different product categories to overall profit.
