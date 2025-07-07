# 🧭 AdventureWorks Data Warehouse ETL

This project contains an ETL pipeline that extracts analytical data from the Microsoft AdventureWorks Data Warehouse, transforms it for reporting use, and loads it into a PostgreSQL destination. It's ideal for practicing business intelligence workflows, dimensional modeling, and dashboard integration.

## 📦 Data Source

- **AdventureWorksDW**: A Microsoft sample data warehouse for sales, finance, product, and customer data
- **Extracted from**: SQL Server or Azure SQL (via ODBC, PyODBC, or SQLAlchemy)
- **Destination**: PostgreSQL schema optimized for reporting

## 🔧 Tech Stack

| Tool          | Purpose                         |
|---------------|---------------------------------|
| Python        | Core ETL logic (extract/transform/load) |
| SQLAlchemy    | Source & target DB integration  |
| Pandas        | Data wrangling and cleaning     |
| Apache Airflow| Pipeline orchestration          |
| PostgreSQL    | Target analytics DB             |
| Power BI / Metabase | (Optional) BI visualization layer |

## 🔄 Pipeline Flow
