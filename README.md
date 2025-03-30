# Adventure-Works---Data-Engineering-Project

This project is an End-to-End Data Engineering pipeline built using Microsoft Azure. It covers the entire ETL process, from data ingestion to transformation and analysis, utilizing Azure Data Factory, Azure Data Lake, Databricks, Azure Synapse Analytics and PowerBI.



![Dashboard](https://github.com/user-attachments/assets/d07fc559-a419-4624-b2b9-f8bbefea6ac4)



### Key Tasks Completed
Created Azure resources for storage and data processing.

Set up Azure Data Lake Storage (ADLS Gen2) and created Bronze, Silver, and Gold containers.

Created Azure Data Factory and configured pipelines & linked services.

Ingested data from an API and a CSV file from GitHub into the Bronze layer.

Implemented dynamic services using parameters in Data Factory.

Used JSON to import all CSV files at once into Azure.

Created a Databricks cluster and configured it with an Azure Catalog.

Developed ETL pipelines using PySpark to transform data.

Created an application in Azure Directory and configured secrets.

Assigned Storage Blob Contributor role to Databricks.

Loaded processed data into Azure Synapse Analytics (Gold Layer).

Created views and external tables in Synapse for querying.

### Tech Stack

Azure Data Factory (ADF) – Data orchestration & ETL pipelines.

Azure Data Lake Storage (ADLS Gen2) – Storage for raw and processed data.

Azure Databricks (PySpark & Apache Spark) – Data transformation & analytics.

Azure Synapse Analytics – Data warehousing & querying.

JSON & Parameterization – Automation for data ingestion.


### Project Workflow
#### Resource Setup:
Created an Azure Resource Group and Storage Account.

Configured Data Lake Storage with Bronze, Silver, and Gold containers.

#### Data Ingestion:
Created Azure Data Factory and configured pipelines.

Set up Linked Services to connect Azure resources.

Pulled data from GitHub (CSV file) and API into Bronze layer.

#### Data Processing & Transformation:
Used JSON configuration to import multiple CSV files at once.

Implemented ForEach iteration in ADF to automate data copying.

Set up Databricks Cluster and created an application in Azure Directory.

Configured Secrets & Storage Permissions (Blob Contributor Role).

#### Synapse Analytics:
Processed data with PySpark in Databricks (Silver Layer).

Loaded transformed data into Azure Synapse Analytics (Gold Layer).

Created Views & External Tables in Synapse for querying and analysis.

#### Power BI:
Integrated Power BI for visualizing and reporting on the data.

Created dashboards and reports for analyzing the processed data stored in Azure Synapse Analytics.

Enabled data refresh from Azure Synapse to ensure up-to-date insights.

Designed interactive reports to provide key metrics and insights to stakeholders.

### Conclusion
This project showcases the creation of an End-to-End Data Engineering pipeline using Microsoft Azure tools. By leveraging Azure Data Factory, Data Lake, Databricks, Synapse Analytics, and Power BI, we successfully automated the ETL process - from data ingestion to transformation and reporting.

The pipeline efficiently handles large datasets, with the processed data visualized through Power BI dashboards to deliver actionable insights. This project highlights Azure's ability to build scalable data pipelines and emphasizes the importance of integrating cloud services with powerful analytics tools to drive informed decision-making.
