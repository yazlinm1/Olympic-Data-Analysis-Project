# Olympic-Data-Analysis-Project
This project demonstrates the steps I followed to build an end-to-end data pipeline on Azure, including data extraction, transformation, storage, analysis, and visualization of the 2021 Tokyo Olympics dataset.

This ![YouTube Tutorial](https://www.youtube.com/watch?v=IaA9YNlg5hM&list=PLVbWJzwYcyv_CFuPqYCErCQOIzD-cqRLV&index=4) helped guide me through the core workflow

# Project Pipeline
![image](https://github.com/user-attachments/assets/ab1ae64c-6e86-43ce-8aa9-74e3ee68304a)

# Setup & Deployment
1. Created Azure Storage Account and Data Lake Gen2 container
2. Used Azure Data Factory to extract olympic data from an HTTP endpoint by using GET request
3. Loaded raw data into Azure Data Lake Storage
4. Wrote transformation code using Azure Databricks (PySpark / Apache Spark SQL)
5. Secured secrets using Azure Key Vault
6. Loaded transformed data into Azure Synapse Analytics
7. Built visualizations using the Synapse Analysis workspace 



# Tech Stack
Azure Data Factory – Data ingestion
Azure Data Lake Storage Gen2 – Data storage
Azure Databricks (PySpark) – Data transformation
Azure Key Vault – Secret key management
Azure Synapse Analytics – Data warehousing and querying
Power BI – Data visualization

