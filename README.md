# E-Commerce Sales Analytics

An end-to-end **E-Commerce Sales Analytics and Data Warehousing project** built using the Northwind dataset.

## About the Project

This project uses the Northwind dataset as a source of transactional sales data and transforms it into an analytical data warehouse.

The project focuses on extracting, cleaning, and transforming data related to customers, orders, products, and categories, followed by storing and analyzing the transformed data to generate meaningful business insights.

The final system will provide insights into areas such as:

* Sales and revenue trends
* Product performance
* Category performance
* Customer purchasing behavior
* Geographical sales
* Order and sales patterns

## Technology Stack

* **Dataset:** Northwind
* **ETL:** Python & Pandas
* **Database:** PostgreSQL
* **Analysis:** SQL
* **Visualization:** Power BI

## Project Pipeline

```text
Northwind Dataset
       ↓
      ETL
       ↓
Data Warehouse
       ↓
   SQL Analysis
       ↓
    Power BI
       ↓
Business Insights
```

## Dataset

The project currently uses the following Northwind tables:

* `Customers`
* `Orders`
* `Order Details`
* `Products`
* `Categories`

The dataset provides the transactional and master data required for the sales analytics use case.

## Objective

The objective of this project is to build a **sales analytics data warehouse** from Northwind's transactional data by integrating customer, order, product, and category information into a structured analytical model. The transformed data will be used to calculate key sales metrics such as **total revenue, order volume, product and category performance, customer spending, average order value, and sales trends over time**, and present these insights through SQL analysis and interactive Power BI visualizations.
