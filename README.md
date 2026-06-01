# walmart-data-engineering-project
End-to-end data engineering project using AWS S3, Snowflake, dbt, Python, and Tableau. Implements Bronze → Staging → Mart architecture with SCD Type 1 &amp; Type 2 dimensional modeling and interactive business reporting.

# Walmart End-to-End Data Engineering Project

## Overview

Built an end-to-end data engineering pipeline using:

- AWS S3
- Snowflake
- dbt
- Python
- Tableau Public

## Architecture

![Architecture](images/architecture.png)

## Data Pipeline

CSV Files
→ AWS S3
→ Snowflake Bronze Layer
→ dbt Staging Layer
→ Dimension & Fact Tables
→ Tableau Dashboard

## Data Model

### Walmart_Date_Dim
- Date_ID
- Store_Date
- IsHoliday

### Walmart_Store_Dim
- Store_ID
- Dept_ID
- Store_Type
- Store_Size

### Walmart_Fact_Table
- Store_Weekly_Sales
- Fuel_Price
- CPI
- Markdown1-5

## Tableau Dashboard

Live Dashboard:

[Tableau Public Link Here]

## Skills Demonstrated

- AWS S3
- Snowflake
- SQL
- dbt
- Dimensional Modeling
- SCD1
- SCD2
- Python
- Tableau
