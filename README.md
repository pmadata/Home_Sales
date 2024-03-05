# Home_Sales

## Setting up Spark Environment and Loading Data:

Installed Spark and Java, set environment variables, and initialized SparkSession.
Loaded data from an AWS S3 bucket into a DataFrame.
## Data Manipulation and Analysis:

Created a temporary view of the DataFrame.
Calculated the average price for a four-bedroom house sold per year.
Calculated the average price of homes with 3 bedrooms and 3 bathrooms per year built.
Calculated the average price of homes meeting specific criteria per year built.
Calculated the average price of homes per "view" rating with runtime measurement.
Cached the temporary table home_sales_df and checked if it's cached.
Reran the query on cached data and compared runtime with the uncached runtime.
Partitioned the DataFrame by the date_built field and saved it in Parquet format.
## Using Parquet Formatted Data:

Read the Parquet formatted data.
Created a temporary table for the Parquet data.
Reran the query on Parquet DataFrame and compared runtime with previous runs.
Uncaching and Checking Cached Table:

Uncached the temporary table home_sales_df.
Checked if the table home_sales_df is no longer cached.
