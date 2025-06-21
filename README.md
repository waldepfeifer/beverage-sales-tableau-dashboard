<img width="767" alt="image" src="https://github.com/user-attachments/assets/f3f8e9bf-ab84-467c-a9d0-042cdb2adb87" />


## Project Overview

This project presents a comprehensive sales performance dashboard for beverage products using Tableau.  
It visualizes revenue, customer behavior, product performance, and category trends based on transactional data.  
The dashboard is designed to support decision-making for both B2B and B2C market segments, with drilldowns by time, region, and product category.

## Objectives

- Monitor key business metrics including revenue, order count, and customer base  
- Identify top-selling products and categories  
- Track sales trends over time at monthly granularity  
- Analyze geographic distribution of revenue across Germany  
- Compare revenue against discounts to evaluate pricing strategy  
- Provide dynamic filtering by time, region, product, and customer type

  <img width="1469" alt="image" src="https://github.com/user-attachments/assets/176d3e93-43c8-4816-94a0-6a4f5f8c6d76" />


## Tools and Technologies

- Tableau Desktop  
- Tableau workbook (.twb)  
- CSV data source  
- Data fields include:
  - Order ID  
  - Customer ID  
  - Customer Type (B2B, B2C)  
  - Product, Category  
  - Region  
  - Order Date  
  - Revenue, Discount  

## Project Structure

beverage-sales-tableau-dashboard/  
├── beverage_sales_kpi_dashboard.twb       – Tableau workbook with all visualizations  
├── beverage_sales.csv                     – Source data used in dashboard (referenced inside Tableau)  
├── README.md                              – Project overview and usage  

## Data Structure

<img width="809" alt="image" src="https://github.com/user-attachments/assets/be055d5c-7ca6-453f-9bec-1233e625742c" />

## Dashboard Features

- Filters:
  - Date range (2021 to 2023)  
  - Product Category  
  - Region  
  - Product  
  - Customer Type (B2B/B2C)  

- KPIs:
  - Total Revenue (€)  
  - Total Orders  
  - Unique Customers  
  - Average Order Value  

- Visual Components:
  - Time series revenue chart  
  - Top products by revenue  
  - Category performance  
  - Revenue by German region (map)  
  - Scatter plot: revenue vs discount per product

## How to Use

1. Open the `.twb` file in Tableau Desktop  
2. Ensure the data file `beverage_sales.csv` is available at the expected path or update the data source  
3. Use filters to explore the dashboard dynamically  
4. Hover, drill down, and export views as needed  

## Requirements

- Tableau Desktop 2021.1 or later  
- beverage_sales.csv file (semicolon-separated, UTF-8 encoding, German locale)

## Mock-Up

<img width="836" alt="image" src="https://github.com/user-attachments/assets/36b57837-8ddf-4c3c-83ae-bb500e73cd5a" />

## License

This project is licensed under the MIT License. See the LICENSE file for details.
