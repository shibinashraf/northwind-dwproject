# Northwind Database ETL Using SQL [ Group 5 Project ]
This project utilizes the Northwind sample database as part of an ETL (Extract, Transform, Load) process, and uses Streamlit to provide a user interface to interact with the underlying data base.

# Application Overview
- Northwind Database (OLTP System): Initial storage of transaction data.
- Landing and Staging Layers: Data extracted from OLTP is held raw in the landing layer, transformed using SCD type 1 in the staging layer.
- Data Warehouse: We load the transformed data, tracking changes with SCD type 2.
- Streamlit Python App: A web-based interface to view and interact with the Northwind database tables. Run procedures to load data, delete tables, and execute custom SQL queries.

# Schema Structure for OLTP
<img width="383" alt="OLTP" src="https://github.com/shibinashraf/northwind-dwproject/assets/28195524/51fb23c2-586c-4aa8-a04c-e94d9dccd216">

# Schema Structure for Datawarehouse
![61000136-a4dc6b80-a354-11e9-9ff2-ae97a9c6ac38](https://github.com/shibinashraf/northwind-dwproject/assets/28195524/b5f329c4-e600-470a-b447-d8fd46f6fedf)

# Repository Structure

- main.py : The streamlit app. Main file to be executed.
- requirements.txt: Required Python dependencies for the project.
- README.md: This file
- sqlfiles/: This directory contains stored procedures for the ETL process, such as data loading, all sql files are available in this folder.


Note: The ETL process here is a simplified one and might require more dynamic handling for production-level databases.
