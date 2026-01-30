# Databricks Lakehouse ETL Pipeline

## Problem Statement
Build a scalable data pipeline to ingest raw transactional data,
clean it, and transform it into analytics-ready tables.

## Architecture
Source → Bronze → Silver → Gold → BI / Analytics

## Tech Stack
PySpark, Databricks, Delta Lake, AWS S3

## Data Flow
1. Raw data ingested into Bronze layer
2. Cleansing & standardization in Silver
3. Aggregated business metrics in Gold

## What I Implemented
• Schema enforcement  
• Incremental loads  
• Data quality checks  
• Partitioning & optimization  

## What I Learned
• Lakehouse architecture  
• PySpark transformations  
• Real-world ETL patterns
