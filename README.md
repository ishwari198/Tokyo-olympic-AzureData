# Olympic Data Analytics Project

## Overview

This project utilizes Azure services to perform data analytics on Olympic data sourced from Kaggle. The data is extracted, transformed, and analyzed using Azure Data Factory, Azure Databricks, and Azure Synapse Analytics.

## Tools Used

- **Azure Data Factory**: Data pipeline creation tool for extracting data from multiple sources.
- **Azure Databricks**: Apache Spark-based data transformation tool for processing data and storing it in Azure Data Lake Gen2.
- **Azure Synapse Analytics**: Analytics platform for running SQL queries and notebooks to gain insights from the data.

## Project Setup

1. **Azure Account Setup**:
    - Create an Azure account and configure storage.
    - Register Microsoft.Storage in the resources provider if validation errors occur.

2. **Data Lake Setup**:
    - Create containers and dictionaries for organizing raw and transformed data.

3. **Data Factory Setup**:
    - Create a data factory and define resources.
    - Author pipelines to transfer data from source to data lake.

4. **Azure Databricks Setup**:
    - Create and configure Databricks instance.
    - Mount data lake for authentication.

5. **GitHub Integration**:
    - Connect Azure Data Factory to GitHub.
    - Load data into data lake from GitHub repository.

6. **Pipeline Validation**:
    - Validate and debug pipelines in Azure Data Factory.

## Usage

1. Clone the repository.
2. Follow setup instructions to configure Azure services.
3. Execute pipelines and run analytics queries as needed.

## Lessons Learned

- **Data Pipeline Building**: Learned how to construct data pipelines using Azure Data Factory for efficient data extraction.
- **Data Transformation with Spark**: Gained experience in data transformation using Apache Spark within Azure Databricks.
- **Analytical Querying**: Utilized Azure Synapse Analytics to run SQL queries for gaining insights into the Olympic data.


