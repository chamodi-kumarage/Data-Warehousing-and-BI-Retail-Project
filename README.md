# Data Warehousing and Business Intelligence Retail Project

This project was completed for the Data Warehousing and Business Intelligence module.

## Project Overview

This project demonstrates the design and development of a complete Data Warehouse and Business Intelligence solution using a fictional retail dataset.

## Tools and Technologies

- Microsoft SQL Server
- SQL Server Management Studio
- SQL Server Integration Services
- ETL
- Star Schema
- Slowly Changing Dimension Type 2
- Fact and Dimension Tables

## Dataset

The project uses a retail customer and transaction dataset containing:

- Customers
- Transactions
- Interactions
- Campaigns
- Customer reviews
- Support tickets

## Data Sources

Multiple source formats were used:

- CSV files
- Excel files
- SQL Server source table

## Data Warehouse Design

The data warehouse follows a Star Schema design.

### Dimension Tables

- DimDate
- DimCustomer
- DimProduct
- DimStore
- DimPaymentMethod

### Fact Table

- FactSales

## ETL Process

The ETL process was developed using SSIS.

Main ETL steps:

1. Load source data into staging tables
2. Clean and transform data
3. Load dimension tables
4. Load the FactSales table
5. Apply accumulating fact table updates

## Key Features

- Staging database
- Data warehouse database
- Star Schema
- SCD Type 2 implementation
- SSIS ETL workflows
- Error handling tables
- Accumulating fact table design

## Project Structure

```text
01_original_csv/
02_excel_sources/
04_ssis_project/
05_screenshots/
06_report/
diagram/
