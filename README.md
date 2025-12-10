# AWS Data Engineering Pipeline

This project demonstrates a serverless **AWS Data Engineering Pipeline** using **S3, Lambda, Glue, Athena, Redshift**, and **Power BI**.

## Architecture Overview

- **S3 (Raw Zone):** Stores raw datasets and log files.  
- **AWS Lambda:** Transforms log files into Parquet format.  
- **AWS Glue:** Performs ETL on main datasets and stores Parquet output.  
- **Amazon Athena:** Ad-hoc SQL queries for validation and profiling.  
- **Amazon Redshift:** Stores curated data for analytics.  
- **Power BI:** Connects to Redshift for dashboards and reporting.

## Key Features

- Fully serverless and scalable  
- Lambda for log file processing  
- Glue ETL for main dataset  
- Parquet-optimized storage  
- Athena for ad-hoc queries  
- Redshift for analytics and Power BI reporting
