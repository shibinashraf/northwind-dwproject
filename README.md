# Northwind Database ETL Using SQL [ Group 5 Project ]
This project utilizes the Northwind sample database as part of an ETL (Extract, Transform, Load) process, and uses Streamlit to provide a user interface to interact with the underlying data base.

# Application Overview
- Northwind Database (OLTP System): Initial storage of transaction data.
- Landing and Staging Layers: Data extracted from OLTP is held raw in the landing layer, transformed using SCD type 1 in the staging layer.
- Data Warehouse: We load the transformed data, tracking changes with SCD type 2.
- Streamlit Python App: A web-based interface to view and interact with the Northwind database tables. Run procedures to load data, delete tables, and execute custom SQL queries.

# Repository Structure

- main.py : The streamlit app. Main file to be executed.
- requirements.txt: Required Python dependencies for the project.
- README.md: This file
- sqlfiles/: This directory contains stored procedures for the ETL process, such as data loading, all sql files are available in this folder.


Note: The ETL process here is a simplified one and might require more dynamic handling for production-level databases.
