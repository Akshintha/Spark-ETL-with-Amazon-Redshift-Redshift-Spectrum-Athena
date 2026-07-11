# Spark ETL with Amazon Redshift, Redshift Spectrum & Athena
This project is about a simple ETL process using Apache Spark and AWS services. It shows how data is transformed and stored for analytics.

## What I Learned
- Read data using PySpark
- Transform and clean data
- Store data in Amazon S3
- Load data into Amazon Redshift
- Query S3 data using Redshift Spectrum
- Create an external table in AWS Athena
- Run SQL queries on external data

## Project Flow
Raw Data
   ↓
Apache Spark
   ↓
Transform Data
   ↓
Amazon S3
   ↓
Redshift Spectrum / Athena
   ↓
Amazon Redshift

## Files
spark-redshift-etl/
│── spark_etl.py
│── redshift_spectrum.sql
│── athena_external_table.sql
└── README.md

## Technologies Used
- Python
- PySpark
- Amazon S3
- Amazon Redshift
- Redshift Spectrum
- AWS Athena
- SQL
