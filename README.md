# Home_Sales
# Home Sales Analysis using PySpark SQL

## Overview
This project analyzes home sales data using PySpark SQL to determine key metrics about home sales. The analysis includes calculating average prices for homes based on various criteria and comparing query performance between cached and uncached data.

## Features
- Data loading from AWS S3 bucket
- Creation of temporary views
- Complex SQL queries for price analysis
- Data caching and uncaching
- Parquet data partitioning
- Performance comparison between different data storage methods

## Technical Details

### Environment Setup
- PySpark SQL
- Findspark
- Java (for Colab implementation)

### Key Analyses
1. Average price of four-bedroom houses by year
2. Average price of homes with three bedrooms and three bathrooms by build year
3. Average price of homes with specific criteria (3 bed, 3 bath, 2 floors, ≥2000 sqft)
4. Average price by view rating for homes ≥$350,000

### Performance Optimization
- Table caching
- Parquet formatting
- Data partitioning

## File Structure
- `Home_Sales.ipynb`: Main analysis notebook
- `Home_Sales_starter_colab.ipynb`: Google Colab version with additional setup
- Parquet data directory (generated during analysis)

## Installation and Usage
1. Clone the repository
2. Install required dependencies
3. Run the Jupyter notebook
4. For Google Colab: Use the Colab version which includes environment setup

## Query Performance
The project includes runtime comparisons between:
- Uncached queries
- Cached queries
- Queries on partitioned parquet data

## Requirements
- Python 3.x
- PySpark
- Jupyter Notebook or Google Colab
- Java (for local implementation)

I have used open source language modules to help me write the code.
