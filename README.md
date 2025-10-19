
# Data Warehouse and Analytics Project
Welcome to the **Data Warehouse and Analytics Project** repository! 🚀
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.
---
## 🛠️ Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using **SQL Server** to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
**Data Sources**: Import data from two source systems (ERP and CRM) provided as **CSV files**.
**Data Quality**: **Cleanse and resolve** data quality issues prior to analysis.
**Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
**Scope**: Focus on the **latest dataset only**; historization of data is not required.
**Documentation**: Provide **clear documentation** of the data model to support both business stakeholders and analytics teams.

---

### 📊 BI: Analytics & Reporting (Data Analytics)

#### Objective
Develop **SQL-based analytics** to deliver detailed insights into:
* **Customer Behavior**
* **Product Performance**
* **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.
---
📁 Repository Structure

data-warehouse-project/
│
├── datasets/                   # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                       # Project documentation and architecture details
│   ├── etl.drawio              # Draw.io file showing ETL methods
│   ├── data_architecture.drawio # Project architecture diagram
│   ├── data_catalog.md         # Dataset descriptions and metadata
│   ├── data_flow.drawio        # Data flow diagram
│   └── data_models.drawio      # Data models (star schema)
│
├── naming-conventions.md       # Naming guidelines for tables, columns, and files
│
├── scripts/                    # SQL scripts for ETL and transformations
│   ├── bronze/                 # Extracting and loading raw data
│   ├── silver/                 # Cleaning and transforming data
│   └── gold/                   # Creating analytical models
│
├── tests/                      # Test scripts and quality checks
│
├── README.md                   # Project overview and instructions
├── LICENSE                     # License information
├── .gitignore                  # Ignored files and directories
└── requirements.txt            # Dependencies and requirements

## 📄 License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

## ✨ About Me

Hi there! I'm **Iqra Nawaz**. I'm a final-year Data Science student at NED University with a focus on data warehousing, analytics, and machine learning. I'm proficient in SQL, Python, and data pipeline development, and I'm on a mission to share knowledge and build robust, data-driven solutions.
