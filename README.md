# WEEK8ASsignment

# NYC Taxi Dataset Analysis Using PySpark (Databricks)

## Project Summary:
This project analyzes real-world NYC Yellow Taxi trip data using PySpark on Databricks. It performs real-time insights, aggregations, and transformations on large-scale datasets.

## Dataset Used:
- Source: [NYC Taxi Trip Data](https://s3.amazonaws.com/nyc-tlc/trip+data/yellow_tripdata_2020-01.csv)
- File: yellow_tripdata_2020-01.csv

## Technologies:
- Apache Spark (PySpark)
- Databricks
- DBFS
- Parquet
- SQL

## Queries Performed:
1. Add Revenue column by summing fare-related charges.
2. Total passengers in NYC by pickup location.
3. Real-time average fare and total earnings by vendor.
4. Moving count of payments by payment mode.
5. Top 2 earning vendors on a given date with distance and passengers.
6. Route with the most number of passengers.
7. Top pickup locations in last 5/10 seconds (simulated).

## Output:
- Code saved as `nyc_taxi_analysis.py`
- Final output written to external parquet and SQL table

