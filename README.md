# Formula 1 Data Engineering Project on Azure Databricks

## Project Overview
This project implements an end-to-end **data engineering pipeline** on **Azure Databricks** to ingest, process, and analyze historical Formula 1 racing data.  
The solution follows modern data engineering best practices, including layered data architecture, scalable storage formats, and distributed processing using Apache Spark.

The primary goal of this project is to demonstrate practical skills in building reliable and maintainable data pipelines using cloud-based big data technologies.

---

## Architecture Overview
The project follows a **Medallion Architecture** approach:

- **Raw Layer**  
  Ingests source data in its original format with minimal transformation.

- **Processed Layer**  
  Applies data cleansing, schema enforcement, and transformations.

- **Presentation Layer**  
  Provides analytics-ready tables optimized for reporting and visualization.

---

## Data Source
- Historical Formula 1 racing datasets 
- Data includes information about:
  - Circuits
  - Races
  - Drivers
  - Constructors
  - Lap times
  - Race results
  - Result 

---

## Technology Stack
- **Azure Databricks**
- **Apache Spark (PySpark & Spark SQL)**
- **Delta Lake**
- **Azure Data Lake Storage Gen2**
- **GitHub (version control)**
- **Azure vault**
  

---

