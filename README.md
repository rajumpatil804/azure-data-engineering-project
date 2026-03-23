# Azure-data-engineering-project
Designed and implemented a scalable data pipeline using Azure Data Factory, Data Lake, and Synapse Analytics for data ingestion, transformation, and analysis.

Phase 1: Dynamic Pipeline Implementation
- Built a metadata-driven pipeline using a JSON configuration file (Git.json)
- Replaced traditional static pipelines with a dynamic and reusable approach
- Automated ingestion of multiple CSV files from GitHub using parameters
- Used ForEach activity to iterate over multiple datasets dynamically
- Eliminated hardcoding by using parameterized datasets and linked services
