# IST3134_Assignment
Cloud-based analysis of 2023 NYC Yellow Taxi Trip Data using PySpark on Amazon EMR and Amazon Athena.
# IST3134 NYC Taxi Analytics

## Project Overview

This project analyses the 2023 NYC Yellow Taxi Trip Data using cloud-based Big Data technologies.

The project compares:

- PySpark on Amazon EMR
- Amazon Athena SQL

The analysis will focus on:

- taxi demand by time and location
- route performance
- fares and recorded electronic tips
- anomalous and invalid trips
- execution time, cost, scalability, and developer effort

## Dataset

Dataset: 2023 Yellow Taxi Trip Data

Official dataset page:
https://data.cityofnewyork.us/Transportation/2023-Yellow-Taxi-Trip-Data/4b4i-vvec/about_data

The project will use all twelve monthly Parquet files for 2023 and the official Taxi Zone Lookup Table.

## Technologies

- AWS Academy Learner Lab
- Amazon S3
- Amazon EMR
- PySpark
- Amazon Athena
- AWS Glue Data Catalog
- GitHub

## Repository Structure

- `src/pyspark/` — PySpark scripts
- `src/athena/` — Athena SQL queries
- `docs/` — dataset profile and cleaning rules
- `outputs/` — final analytical results
- `screenshots/` — implementation evidence
- `report/` — report drafts and supporting material
