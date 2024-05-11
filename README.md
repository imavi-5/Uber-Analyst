# Project Overview

This project involves analyzing Uber ride data through various stages including raw data storage on Google Cloud, Extract Transform Load (ETL) using Mage AI, analysis on BigQuery, and visualization through a dashboard on Locket Studio.

## Objectives
- Analyze Uber ride data efficiently.
- Create a user-friendly dashboard for visualizing key metrics.

## Steps Taken

### 1. Raw Storage on Google Cloud
- Stored Uber ride data securely in a Google Cloud Storage bucket.
- Uploaded the dataset `uber_data.csv` and made it public.
- Created a bucket named `uber_data_engineering`.

### 2. Extract Transform Load (ETL) with Mage AI
- Deployed Mage AI on a Google Compute Engine instance.
- Installed required packages like Python and Mage AI.
- Configured firewall rules to accept requests from all IPs.
- Utilized Mage AI to automate the ETL process by creating pipelines for data loading and transformation.
- Transformed the data into a fact table and 7 dimension tables.

### 3. Analysis on BigQuery
- Loaded the transformed data into BigQuery.
- Executed SQL queries to derive insights such as average fare amounts, total fare amounts per vendor, and joining tables for comprehensive analysis.

### 4. Dashboard Creation with Locket Studio
- Connected Locket Studio to BigQuery.
- Authorized and added dataset tables to the report.
- Designed a dashboard with interactive features including filters based on vendor ID, payment type, and rate code.
- Created summary sections displaying key metrics like record count, total amount, average trip distance, fare amount, and tip amount.
- Added visualizations such as bar charts to represent rate code and payment type distributions.

## Insights Gained
- Vendor performance evaluation based on average fare amounts.
- Analysis of payment trends to understand customer preferences.
- Examination of trip patterns to identify popular routes.
- Visualization of geographical data to pinpoint high-demand areas.

