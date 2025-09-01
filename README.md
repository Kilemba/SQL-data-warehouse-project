# SQL-data-warehouse-project
Welcome to the **SQL-data-warehouse-project** repository.
This project demnstrates building a modern data warehouse with SQL server, including ETL processes, data modelling, and analytics solution, from data warehouse to generating actionable insights. 
## Project Requirements
## 📖 Project Overview

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.
   
   <img width="659" height="330" alt="Data architecture" src="https://github.com/user-attachments/assets/34ff09b4-45f3-479d-b21d-f9652eb0e4f9" />

3. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
4. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
5. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.

- ---
### Building the data warehouse (Data Engineering)
#### Objectives of the project
This project aims at developing a modern data warehouse using SQL server to consolidate  sales data, enabling analytical reporting and informed decision making.

#### Specifications
--> **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.

--> **Data Quality**: Cleanse and resolve data quality issues prior to analysis.

--> **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.

--> **Scope**: Focus on the latest dataset only; historization of data is not required.

--> **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

### BI: Analytics & Reporting (Data Analysis)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making. 

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
```
---
## 🛡️ License

This project is not licensed. 

## 🌟 About Me

Hi there! I'm **Caleb Kilemba**. I’m a data Engineer who aims at designing and maintaining reliable data pipelines that transform raw information into actionable insights, enabling smarter decision-making and business growth.
