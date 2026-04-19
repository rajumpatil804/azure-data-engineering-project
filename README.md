# Azure-data-engineering-project
Designed and implemented a scalable data pipeline using Azure Data Factory, Data Lake, and Synapse Analytics for data ingestion, transformation, and analysis.

Phase 1: Dynamic Pipeline Implementation
- Built a metadata-driven pipeline using a JSON configuration file (Git.json)
- Replaced traditional static pipelines with a dynamic and reusable approach
- Automated ingestion of multiple CSV files from GitHub using parameters
- Used ForEach activity to iterate over multiple datasets dynamically
- Eliminated hardcoding by using parameterized datasets and linked services

Phase 2: Data Transformation and Cleaning using Databricks

- Performed data transformation using Azure Databricks with PySpark.
- Cleaned and processed raw data by handling null values, duplicates, and inconsistent formats.
- Applied necessary data transformations such as filtering, column selection, and data type conversions.
- Implemented structured data processing for better analytics and reporting.
- Stored the transformed data into Azure Data Lake in a refined format.
- Improved data quality and consistency for downstream analysis.
