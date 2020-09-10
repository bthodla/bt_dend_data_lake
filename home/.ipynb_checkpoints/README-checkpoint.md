# Data Lake Project

## Project Scope

With an increase in the user base and number of songs in its database, Sparkify wants to move this data into a data lke. The current data resides in Amazon S3 in JSON format and includes the following:

- User Activity Logs
- Song Metadata

The scope of this project is to build an ETL pipeline that extracts this data from S3, process it using Spark and write the outputs back to S3 but in *paquet* format. As a part of the process, we should also split the data into facts and dimensions. And when writing all time-variant data, the data should be partitioned by time and any other appropriate attributes.

## Schema Design
