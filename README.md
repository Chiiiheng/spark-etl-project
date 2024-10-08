# Portable stock trading ETL pipeline

## Overview
This repo contains a portable ETL (Extract, Transform, Load) pipeline designed to fetch, process, and aggregate large volumes of stock trading data into daily reports. The pipeline leverages Spark, Delta Lake, S3, and open-source data quality framework to ensure efficient data extraction, transformation, storage, and analysis. It is well-suited for scenarios where users need to frequently collect and aggregate trading data for analysis, reporting, or further processing.

## Architecture
### Technology and Tools
- **Python:** Core programming language used for scripting the ETL processes.
- **API:** The pipeline uses the Alpha Vantage API to fetch real-time trading data.
- **PySpark:** Used for distributed data processing, enabling efficient handling of large datasets.
- **MinIO:** Object storage solution used for storing raw and processed data. Compatible with S3 APIs.
- **Delta Lake:** Provides scalable and reliable data storage, enabling the management of different data layers (bronze, silver).
- **Docker:** Containers are used to standardize the development environment and streamline deployment.
- **Cron:** Cron jobs are applied for scheduling regular data collection and processing tasks.
- **Make:** Used to simplify and manage the execution of tasks within the project, including setup, build and deployment.

### Data Flow
<img width="993" alt="Screenshot 2024-08-17 at 18 27 28" src="https://github.com/user-attachments/assets/4018ebed-8fdc-405c-9f26-714a09211f3f">



## Welcome to My First Data Engineering Project!
