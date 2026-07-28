# E-Commerce Sales Data Warehouse

An end-to-end data warehousing project that transforms raw e-commerce transaction data into a centralized PostgreSQL data warehouse for business intelligence and analytics.

## Overview

under review 08 - This project demonstrates the design and implementation of an ETL pipeline that extracts, cleans, transforms, and loads e-commerce sales data into a star schema optimized for analytical queries. The warehouse enables efficient reporting on sales performance, customer purchasing behavior, and product trends.

## Features

- ETL pipeline for extracting, transforming, and loading sales data
- Data cleaning and validation
- Star schema dimensional modeling
- PostgreSQL data warehouse
- Optimized SQL queries for analytics
- Business intelligence reporting

## Tech Stack

- Python
- PostgreSQL
- SQL
- Pandas
- ETL
- Data Warehousing
- Star Schema

## Data Warehouse Schema

```
Raw Sales Data
       │
       ▼
Extract
       │
       ▼
Transform
 ├── Clean Data
 ├── Validate Records
 ├── Normalize Fields
 └── Create Dimensions
       │
       ▼
Load
       │
       ▼
PostgreSQL Data Warehouse
       │
       ▼
Star Schema
 ├── FactSales
 ├── DimCustomer
 ├── DimProduct
 ├── DimDate
 └── DimCategory
```

## Analytics

The warehouse supports analysis such as:

- Revenue trends
- Top-selling products
- Customer purchasing behavior
- Sales by category
- Monthly and yearly sales performance
- Average order value

## Learning Outcomes

- ETL pipeline development
- Dimensional data modeling
- Data warehouse design
- SQL optimization
- Business intelligence analytics

---

Built as a portfolio project to demonstrate data engineering, SQL, ETL, and data warehousing concepts.
