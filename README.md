Tokyo-Olympic-Azure-Data-Engineering-Project
Project Overview
The main goal of this project is to learn how to use different Azure tools to build a data pipeline. This project explores how to connect and use services like Azure Data Factory, Azure Data Lake, Databricks, and Azure Synapse Analytics. By working through this pipeline, the project helps build practical skills in moving, transforming, and analyzing data within the Azure platform.# AZDE-Project
Architecture Image

Architecture Image
Pipeline Image

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
