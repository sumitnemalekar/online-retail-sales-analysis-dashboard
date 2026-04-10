 
# Online Retail Sales Analysis Dashboard

## Project Overview
This project analyzes online retail sales data from a UK-based e-commerce business between December 2010 and December 2011.

The goal of this project is to identify:
- Top-selling products
- Revenue trends over time
- High-performing countries
- Best customers
- Business growth opportunities

## Dataset
Dataset: Online Retail Dataset
Source: UCI Machine Learning Repository

The dataset contains:
- Invoice numbers
- Product codes
- Product descriptions
- Quantities sold
- Invoice dates
- Unit prices
- Customer IDs
- Country information

## Tools Used
- Power BI
- Power Query
- CSV Data Cleaning

## Data Cleaning Steps
The following cleaning steps were performed:
- Removed rows where Quantity <= 0
- Removed rows where UnitPrice <= 0
- Removed blank product descriptions
- Removed null Customer IDs where needed
- Created a Revenue column
- Created Month, Year, and Day Name columns

## Key Business Questions
1. Which products generate the most revenue?
2. Which countries generate the most sales?
3. How do sales change over time?
4. Which customers contribute the most revenue?
5. Which days have the highest sales activity?

## Dashboard Features
- KPI cards for revenue, orders, customers, and quantity sold
- Revenue trend line chart
- Top 10 products by revenue
- Revenue by country map
- Top customers chart
- Revenue by day of week chart
- Interactive slicers for country, year, month, and product

## Key Insights
- The United Kingdom generates the highest revenue.
- Revenue peaks during November and December.
- A small number of products generate a large portion of total revenue.
- International markets such as France, Germany, and the Netherlands perform strongly.
- Repeat customers contribute significantly to total sales.

## Recommendations
- Increase inventory before holiday months.
- Focus marketing on top-performing countries.
- Retain top customers with loyalty programs.
- Promote low-performing products through bundles and discounts.

## Files Included
- Cleaned CSV dataset
- Power BI dashboard (.pbix)
- Dashboard screenshots
- Final report PDF
