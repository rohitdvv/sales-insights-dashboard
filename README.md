# Sales Insights Dashboard

A Power BI data analysis project that provides visual insights into sales performance, trends, and market behavior.

## Project Overview

This project analyzes sales data to uncover actionable business insights using Microsoft Power BI. It includes an interactive dashboard built on a MySQL database of transactional sales records.

## Files

| File | Description |
|------|-------------|
| `sales_insights.pbix` | Core Power BI report with sales analysis |
| `Dash board.pbix` | Updated dashboard with additional visuals |
| `Dash board.pdf` | PDF export of the final dashboard |

## Key Insights

- Revenue breakdown by market and region
- Year-over-year and month-over-month sales trends
- Top customers and product performance
- Currency normalization (INR / USD) for accurate revenue totals

## Tools & Technologies

- **Microsoft Power BI** — data modeling, DAX measures, interactive visuals
- **MySQL** — source database with transactions, customers, products, and date tables
- **SQL** — data exploration and validation queries

## Data Source

The underlying data is a MySQL sales database (`db_dump.sql`) containing:
- Customer records across multiple markets
- Product and transaction data
- Date dimension table for time-intelligence analysis

## Setup

1. Import `db_dump.sql` into a local MySQL instance
2. Open `sales_insights.pbix` or `Dash board.pbix` in Power BI Desktop
3. Update the data source connection to point to your local MySQL server
4. Refresh the data to load the latest records

## Author

Rohit Dusanapudi — [GitHub](https://github.com/rohitdvv)
