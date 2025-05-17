# E-commerce Sales Analytics Dashboard

This project explores and analyzes e-commerce sales data using Google BigQuery and visualizes key insights through a custom dashboard built with Looker Studio.

The data includes customer purchases from different countries, covering details like product names, prices, quantities, and invoice dates. The goal is to track sales trends, identify top products, and better understand customer behavior across regions.

---

## Project Overview

Fields in the dataset:
- Country
- CustomerID
- UnitPrice
- InvoiceDate
- Quantity
- Description
- StockCode
- InvoiceNo

The CSV file was uploaded to BigQuery, where SQL queries were used to filter, sort, and calculate metrics like total sales. These results were visualized in Looker Studio through charts, filters, and KPIs.

---

## Tools Used

- Google BigQuery (for storing and querying data)
- Looker Studio (for dashboard and visualization)
- SQL (for data analysis and transformations)
- Google Cloud Platform

---

## Dashboard Features

- Sales by Country (Geo map)
- Top Selling Products by Quantity
- Daily Sales Trend (Line chart)
- Total Sales calculated using Quantity × UnitPrice
- Interactive filters: Country, Product Description, and Invoice Date

---

## Folder Structure

ecommerce-analytics/
│
├── bigquery/
│   ├── create_table.sql         → Table creation script
│   ├── sample_query.sql         → Example SQL queries
│   ├── schema.json              → Optional schema definition
│   └── sample_data.csv          → Sample dataset (from CSV)
│
├── looker-studio/
│   ├── dashboard_overview.pdf   → Overview or notes on dashboard design
│   ├── screenshots/             → Images of the report
│   └── report_link.txt          → Public Looker Studio dashboard link
│
└── README.md                    → Project documentation

---

## How to Reproduce

1. Upload `sample_data.csv` to BigQuery.
2. Use the `create_table.sql` script to create the table.
3. Run the sample queries to generate insights.
4. Connect the BigQuery table to Looker Studio.
5. Design the dashboard using charts, filters, and calculated fields.

---

## Notes

This is a beginner-friendly analytics project and a great example of using cloud-based tools to turn raw data into useful business insights. It demonstrates practical SQL skills, data modeling, and dashboard creation.

---

Created by: **Sainath Kotage**
