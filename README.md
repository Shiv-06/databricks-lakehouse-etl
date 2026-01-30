# Databricks Lakehouse ETL Pipeline (Bronze → Silver → Gold)

## Problem Statement
Build a scalable ETL pipeline to ingest raw transactional data, clean it, and create analytics-ready datasets.

## Architecture
Source (CSV/API/DB) → Bronze (Raw) → Silver (Clean) → Gold (Business) → BI / Analytics

## Tech Stack
PySpark, Databricks, Delta Lake, AWS S3 (or local)

## Data Flow
1. Ingest raw data into Bronze tables
2. Clean + standardize into Silver tables
3. Create aggregated metrics into Gold tables
4. Run data quality checks for nulls/duplicates

## Deliverables
• Bronze/Silver/Gold tables  
• Data quality checks  
• Reproducible folder structure  
• Documentation & run steps
