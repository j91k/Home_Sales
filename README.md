# Home Sales Analysis

This project analyzes home sales data using PySpark SQL. It demonstrates various data processing and querying techniques on a large dataset of home sales information.

## Features

- Create and manipulate Spark DataFrames
- Perform simple SQL queries on home sales data
- Cache and uncache temporary tables
- Work with Parquet file format
- Compare query performance between different data storage methods

## Key Analyses

1. Average price of four-bedroom houses sold each year
2. Average price of homes with three bedrooms and three bathrooms by year built
3. Average price of homes with specific criteria (3 bed, 3 bath, 2 floors, ≥2000 sqft) by year built
4. Average price of homes by "view" rating for homes ≥$350,000

## Technical Highlights

- Use of Spark SQL for data querying
- Caching of temporary tables to improve performance
- Partitioning data by "date_built" field
- Comparison of query runtimes between cached and uncached data

## Requirements

- PySpark
- Jupyter Notebook or similar environment to run the .ipynb file

## Usage

1. Clone the repository
2. Ensure PySpark is installed and configured
3. Open and run the Jupyter Notebook `Home_Sales.ipynb`

## Results

The notebook includes detailed results for each analysis, including query runtimes and performance comparisons between different data storage methods.
