
# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---
##  Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

---
##  Project Overview

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.

 This repository is an excellent resource for professionals and students looking to showcase expertise in:
- SQL Development
- Data Architect
- Data Engineering  
- ETL Pipeline Developer  
- Data Modeling  
- Data Analytics  

## Repository structure
.
├── datasets/                           # Raw CSV input files (CRM, ERP)
├── docs/
│   └── Create_data_catalog.md          # Data catalog for tables/views
├── scripts/
│   ├── bronze/
│   │   ├── ddl_bronze.sql              # DDL to create raw tables
│   │   └── proc_load_bronze.sql        # Stored procedure to load raw data
│   ├── silver/
│   │   ├── ddl_silver.sql              # DDL to create cleaned tables
│   │   └── proc_load_silver.sql        # Stored procedure to clean/transform data
│   ├── gold/
│   │   └── ddl_gold.sql                # DDL to create business-ready views (star schema)
│   └── init_database.sql              # Create database and schema structure
├── tests/
│   └── quality_checks_silver.sql      # Data quality checks for Silver layer
├── LICENSE
└── README.md                          # You are here


