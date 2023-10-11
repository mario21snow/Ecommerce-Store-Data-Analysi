
# Dashboard
![Ecommerce-Store-Data-Analysis-dashboard](https://user-images.githubusercontent.com/60383145/222998126-5185133f-6f7b-4bda-bb44-494a7585c734.# E-Commerce Store Annual Sales Report 2022

## Objective

The E-Commerce Store aims to create an annual sales report for 2022 to gain a deeper understanding of their customers and strategize for increased sales in 2023.

## Key Questions

1. Compare Sales and Orders using a single chart.
2. Identify the month with the highest Sales and orders.
3. Analyze the gender-based purchasing behavior (Men vs. Women).
4. Explore different order statuses.
5. List the top 10 states in terms of sales.
6. Examine the relationship between age and gender based on the number of orders.
7. Determine the most popular channel for purchased items.
8. Identify the highest-selling product categories.

## About the Data-set

This comprehensive project revolves around the sales of the E-commerce Store. Using the dataset, we've extracted valuable insights and presented them in a dashboard. The dataset comprises 19 columns and a total of 31,048 rows.

## Data Cleaning

1. Removed unnecessary and irrelevant columns like Currency and Ship-country due to the Indian market focus.
2. Checked for and removed duplicate values.
3. Dealt with incomplete and null values in the data for better insights.
4. Replaced and modified columns like Gender and Size.
5. Checked for typographical errors.

## Data Processing

1. Introduced an Age Group column to bucket ages into Young, Adult (30+), and Senior (50+) categories.
   - Using Formula: `=IF(E2>=50,"Senior",IF(E2>=30,"Adult","Young")`
2. Created a new column for Month to facilitate insights.
   - Using Formula: `=TEXT(H2,"mmm")`

## Data Analysis

1. Created a Pivot Table for analyzing Orders vs. Sales.
2. Developed a Pivot Table for Order Status analysis.
3. Constructed a Pivot Table to analyze Sales in the top 10 states.
4. Generated a Pivot Table to compare Men vs. Women purchases.
5. Established a Pivot Table to explore the relationship between Age and Gender.
6. Created a table to determine the most popular channel for purchasing orders.

## Data Report/Visualization

Merged all the Pivot tables and connected them via slicers to create the "E-commerce Store Data Analysis Report 2022 - Final Report."

## Client Insights

Dear Client,
First and foremost, thank you for providing us with this dataset for analysis. Here's an overview of the insights we've gained from the report:
1. Women are more likely to make purchases compared to men, accounting for approximately 65% of the customer base.
2. The top three states in terms of sales are Maharashtra, Karnataka, and Uttar Pradesh.
3. The adult age group (30-49 years) makes the most significant contribution, accounting for approximately 50% of the sales.
4. Amazon is the most popular platform for purchasing products.

## Action for 2023

To enhance sales in 2023, we recommend targeting women customers in the age group of 30-49 years residing in Maharashtra, Karnataka, and Uttar Pradesh. This can be achieved by showcasing ads, offers, and coupons on platforms like Amazon, Flipkart, and Myntra.
