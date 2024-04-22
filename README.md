# Project 1 – databricks

# Yelp Data Processing Project

## Overview
This project aims to process raw Yelp data and create a unified dataset for querying. The processed dataset will be used to answer various business questions.

## Technologies Used
- Databricks: The project is implemented using Databricks notebooks.
- Apache Spark: Spark is used for data processing and manipulation.
- Delta Lake: Delta Lake is utilized for managing data versions and ensuring data integrity.
- Python: Python programming language is used for data processing and scripting.

## Steps
1. **Raw to Bronze**: The raw JSON data files are read using Spark and combined into a Bronze Delta table. This step involves data reading, transformation, and joining.
2. **Bronze to Silver**: The Bronze Delta table is cleaned and transformed into a Silver Delta table. Data cleaning involves removing unnecessary columns, filtering out invalid records, and removing duplicates.
3. **Query for Business Questions**: Various business questions are answered by querying the Silver Delta table using Spark SQL. Examples of queries include counting businesses by state and city, identifying the most common business types, analyzing review patterns, and calculating average review stars for each business.

## Folder Structure
- `/FileStore/tables/`: Contains raw JSON data files.
- `.pynb`: Databricks notebooks for data processing and querying.
- `README.md`: This file providing an overview of the project.

## Running the Project
1. Ensure you have access to a Databricks environment.
2. Upload the raw data files to a suitable storage location accessible from Databricks.
3. Create a Databricks notebook and copy the code from the provided notebooks or implement your own code based on the provided overview.
4. Execute the notebook cells step by step to process the data and answer business questions.
5. Review the results and further refine the queries as needed.



