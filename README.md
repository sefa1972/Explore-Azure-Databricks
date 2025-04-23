# Explore-Azure-Databricks

This project is part of the **DP-203: Azure Data Engineer** learning module on the Microsoft Learn platform. In this lab, data is analyzed and visualized using the **Azure Databricks** platform.

## Objective

The goal of this lab is to learn how to analyze data, create visualizations, and perform SQL queries by creating a Spark cluster within the Azure Databricks environment.

## Technologies Used

- Azure Databricks (13.3 LTS, Spark 3.4.1)
- Apache Spark
- PySpark
- Azure Cloud Shell (PowerShell)
- Git
- Microsoft Azure Portal

## Tasks Performed

1. Cloned the GitHub repository containing the lab files via Azure Cloud Shell.
2. Created an Azure Databricks workspace using a PowerShell script.
3. Created a single-node Spark cluster in Azure Databricks.
4. Uploaded the `products.csv` file to Databricks.
5. Loaded and analyzed data as a `DataFrame` using PySpark.
6. Created a visual bar chart from the data.
7. Created a table named `products` and queried it using SQL.

## Folder Structure

> Notes:  
> - Environment: Single Node, Photon Acceleration enabled  
> - Databricks Runtime: 13.3 LTS  
> - Node type: Standard_DS3_v2  

## Outcome

At the end of the lab:

- I learned the basics of working with the Azure Databricks platform.
- I performed data analysis using PySpark.
- I worked with tables using SQL.
- I utilized visualization tools effectively.

## Cleanup

To avoid unnecessary Azure costs, it is important to delete the resources created. You can do this by deleting the resource group from the Azure portal.
