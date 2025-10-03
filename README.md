# Azure-Data-Engineering-Project-End-To-End
End-to-end Medallion Architecture project on Azure: data ingested from On-Prem to ADLS via ADF, cleaned &amp; transformed in Databricks, warehoused in Synapse for SQL-based analytics, with Key Vault securing sensitive credentials, and insights visualized through interactive Power BI dashboards.

Project Architecture
![Untitled-1](https://github.com/user-attachments/assets/b1fe3074-97b9-48d3-bfa1-063770c04eed)

<img width="1287" height="724" alt="image" src="https://github.com/user-attachments/assets/54d02cbf-67c4-46a3-8882-acc27be6b6c0" />

This project addresses a critical business need by building a comprehensive data pipeline on Azure. The goal is to extract customer and sales data from an on-premises SQL database, transform it in the cloud, and generate actionable insights through a Power BI dashboard. The dashboard will highlight key performance indicators (KPIs) related to gender distribution and product category sales, allowing stakeholders to filter and analyze data by date, product category, and gender.
Business Requirements

The business has identified a gap in understanding customer demographics—specifically gender distribution—and how it influences product purchases. The key requirements include:

    Sales by Gender and Product Category: A dashboard showing the total products sold, total sales revenue, and a gender split among customers.
    Data Filtering: Ability to filter the data by product category, gender, and date.
    User-Friendly Interface: Stakeholders should have access to an easy-to-use interface for making queries.

Solution Overview

To meet these requirements, the solution is broken down into the following components:

    Data Ingestion:
        Extract customer and sales data from an on-premises SQL database.
        Load the data into Azure Data Lake Storage (ADLS) using Azure Data Factory (ADF).

    Data Transformation:
        Use Azure Databricks to clean and transform the data.
        Organize the data into Bronze, Silver, and Gold layers for raw, cleansed, and aggregated data respectively.

    Data Loading and Reporting:
        Load the transformed data into Azure Synapse Analytics.
        Build a Power BI dashboard to visualize the data, allowing stakeholders to explore sales and demographic insights.

 

Technology Stack

    Azure Data Factory (ADF): For orchestrating data movement and transformation.
    Azure Data Lake Storage (ADLS): For storing raw and processed data.
    Azure Databricks: For data transformation and processing.
    Azure Synapse Analytics: For data warehousing and SQL-based analytics.
    Power BI: For data visualization and reporting.
    Azure Key Vault: For securely managing credentials and secrets.
    SQL Server (On-Premises): Source of customer and sales data.

