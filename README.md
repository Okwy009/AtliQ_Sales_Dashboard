# AtliQ Sales Dashboard with Power BI

## Overview
This repository contains the Power BI dashboard for sales data analysis, focused on delivering key insights into sales performance across various dimensions, including products, customers, and markets. The Power BI file (Sales_Data.pbix) provides interactive visualizations and analytics to support decision-making and optimize sales strategies.

## Background

Using SQL and Tableau to Create dashboards that will give insights to the Sales Director at AtliQ to help make informed business decisions.

## Tools Used
During the course of the project I used the following:

- **SQL:** For accessing and querying the database.

- **Tableau:** For creating Visualizations and Dashboard.

- **Git & GitHub:** For version control and sharing my Python code and analysis, ensuring collaboration and project tracking.

## Files

- **db_dump.sql:** This file contains the dataset required for this analysis.

- **Sales_Data.pbix:** The Power BI file containing the sales dashboard.
- **README.md:** Documentation for the project.

## Key Features

- **Sales Performance Overview:** Displays total sales amount, sales quantity, and normalized sales for better comparison across regions and currencies.
- **Top Performing Products:** Visual breakdown of the products that contribute the most to sales.
- **Customer Segmentation:** Insight into sales patterns by customer groups.
- **Market Analysis:** Performance comparison across different markets.
- **Dynamic Filters:** Interactive filters to explore the data by product, customer, market, and order date.

## Data Model
The data in this Power BI file is structured around the following key fields:

- **product_code:** Unique code for each product.
- **customer_code:** Unique code for each customer.
- **market_code:** Represents different sales markets.
- **order_date:** Date of the sales transaction.
- **sales_qty:** Quantity of products sold.
- **sales_amount:** Total revenue from the sale.
- **currency:** The currency used in the transaction.
- **norm_sales_amount:** Normalized sales amount to account for different currencies.

## Usage Instructions
1. Download the Sales_Data.pbix file from this repository.
2. Open the file using Power BI Desktop.
3. If prompted, update the data source to point to your own data file (if applicable).
4. Interact with the dashboard by using filters and visualizations to gain insights into sales data.

## Visuals
The dashboard contains several types of visualizations to help interpret the data effectively:

- Bar charts for sales by product, customer, and market.
- Line graphs showing trends over time.
- Tables for detailed data views.
- KPI cards for total sales and sales quantities.

## Requirements
- **Power BI Desktop:** Download it from Power BI Desktop.
- **Data Source:** If you want to update the data source, ensure that the structure matches the existing data model.

## How to Customize
1. Open the .pbix file in Power BI.
2. Modify the data connections or add new data sources as needed.
3. Customize the visuals or create new reports to suit your needs.
4. Publish the report to Power BI Service or share the .pbix file with other users.