Tokyo-Olympic-Azure-Data-Engineering-Project
Project Overview
The main goal of this project is to learn how to use different Azure tools to build a data pipeline. This project explores how to connect and use services like Azure Data Factory, Azure Data Lake, Databricks, and Azure Synapse Analytics. By working through this pipeline, the project helps build practical skills in moving, transforming, and analyzing data within the Azure platform.# AZDE-Project
Architecture Image
![385345940-422417d4-9465-4eca-9408-491643c43cca-1](https://github.com/user-attachments/assets/34bc5b54-3fd6-4514-a888-1e874c47cf7f)

Architecture Image
![385345142-5fb2bab5-db71-46d5-aaf5-030f2f6d041e](https://github.com/user-attachments/assets/028a5e32-01a7-44e2-b188-2860ae4c80ff)


ADF_Pipeline
Workflow
Data Extraction

    Extracted data from GitHub using an HTTP connection.
    Used Azure Data Factory (ADF) to copy data to Azure Data Lake Gen2 (Raw folder).

Data Transformation

    Created a mount point in Databricks pointing to the Raw folder in Azure Data Lake Gen2.
    Performed data transformations in Databricks and loaded the processed data into the Processed folder in Azure Data Lake Gen2.

Data Loading & Analytics

    Created a database in Azure Synapse Analytics.
    Created tables within the Azure Synapse database.
    Executed SQL analytical scripts to generate insights.

Technologies Used

    Azure Data Factory: For data extraction and migration.
    Azure Data Lake Gen2: For data storage.
    Databricks (with PySpark): For data transformation.
    Azure Synapse Analytics: For data analysis and creating views.
    Programming Languages: SQL, PySpark.
