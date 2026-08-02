# ETL-process.
I built two ETL processes using airflow, phyton and SQL, 
Global Geographic Data ETL Pipeline using Apache Airflow, Python, SQL & PostgreSQL
# Project Overview
I Designed and implemented an automated ETL pipeline to extract, transform, and load global geographic reference data into a PostgreSQL data warehouse. The solution used Python, REST APIs, Pandas, SQLAlchemy, PostgreSQL, and Apache Airflow to automate data ingestion, transformation, storage, and scheduling for downstream analytics.
# Situation
Organizations frequently rely on multiple external reference datasets (countries, languages, currencies, and continents) for reporting, customer segmentation, localization, and business intelligence. However, these datasets are often distributed across separate sources and require manual updates, creating inconsistencies, duplicate effort, and outdated information.
# The objective was to build an automated data pipeline that continuously retrieves standardized geographical reference data and stores it in a structured database for reporting and analytical use.
# Kindly take note of the following task.
I developed an automated ETL solution that is capable of:
Extracting country, language, currency, and continent data from public REST APIs.
Cleaning and standardizing inconsistent JSON structures.
Transforming raw data into normalized relational tables.
Loading cleaned data into PostgreSQL.
Automating execution and monitoring using Apache Airflow.
Providing a reliable source of reference data for reporting and analytics.
# Dataset: https://raw.githubusercontent.com/annexare/Countries/master/data/
[Geographical Data, ETL pipeline.docx](https://github.com/user-attachments/files/30625824/Geographical.Data.ETL.pipeline.docx)


