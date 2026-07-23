# 🏅 Tokyo Olympics Azure Data Engineering Project

## 📌 Project Overview

This project demonstrates an end-to-end Azure Data Engineering pipeline built using Microsoft Azure services. The pipeline ingests the Tokyo Olympics 2021 dataset from GitHub, stores it in Azure Data Lake Storage Gen2, performs data transformation using Azure Databricks (PySpark), analyzes the transformed data with Azure Synapse Analytics, and visualizes insights using Power BI.

The project showcases a modern cloud-based ETL workflow and highlights how Azure services can be integrated to build scalable data engineering solutions.

---

## 🛠️ Technologies Used

- Azure Data Factory
- Azure Data Lake Storage Gen2
- Azure Databricks
- PySpark
- Azure Synapse Analytics
- Power BI
- GitHub
- SQL

---

## 📂 Dataset

The project uses the **Tokyo Olympics 2021** dataset, which includes information about:

- Athletes
- Coaches
- Teams
- Medals
- Gender Participation

---

## 🏗️ Project Architecture

```
GitHub Dataset
       │
       ▼
Azure Data Factory
       │
       ▼
Azure Data Lake Storage Gen2 (Raw Data)
       │
       ▼
Azure Databricks (PySpark Transformation)
       │
       ▼
Azure Data Lake Storage Gen2 (Transformed Data)
       │
       ▼
Azure Synapse Analytics
       │
       ▼
Power BI Dashboard
```

---

## 🔄 Workflow

### Step 1 – Data Ingestion

- Read CSV files from GitHub.
- Copy data into Azure Data Lake Storage Gen2 using Azure Data Factory.

### Step 2 – Data Storage

- Store raw datasets inside the Raw container of Azure Data Lake.

### Step 3 – Data Transformation

- Read raw data using Azure Databricks.
- Clean and transform datasets using PySpark.
- Remove null values and duplicates.
- Convert data types.
- Save transformed data in Parquet format.

### Step 4 – Data Analysis

- Load transformed data into Azure Synapse Analytics.
- Perform SQL-based analysis.

### Step 5 – Visualization

- Connect Power BI with Azure Synapse.
- Build interactive dashboards and reports.

---

## 📁 Project Structure

```
Tokyo-Olympics-Azure-Data-Engineering/
│
├── data/
│   ├── athletes.csv
│   ├── coaches.csv
│   ├── entriesgender.csv
│   ├── medals.csv
│   └── teams.csv
│
├── notebooks/
│   └── TokyoOlympicsTransformation.ipynb
│
├── sql/
│   └── analysis.sql
│
├── architecture/
│   └── architecture.png
│
├── README.md
│
└── LICENSE
```

---

## 📊 Key Features

- End-to-End Azure Data Engineering Pipeline
- Cloud-based ETL Workflow
- Data Ingestion using Azure Data Factory
- Data Storage using Azure Data Lake Gen2
- Data Transformation using Azure Databricks & PySpark
- SQL Analytics using Azure Synapse
- Interactive Dashboard using Power BI

---

## 📚 Skills Demonstrated

- Azure Data Factory
- Azure Data Lake Storage Gen2
- Azure Databricks
- PySpark
- Azure Synapse Analytics
- SQL
- ETL Pipeline Design
- Data Engineering Fundamentals
- Data Visualization

---

## 📸 Project Screenshots

Add screenshots of:

- Azure Data Factory Pipeline
- Azure Data Lake Storage
- Azure Databricks Notebook
- Azure Synapse Queries
- Power BI Dashboard

---

## 🚀 Future Enhancements

- Implement Incremental Data Loading
- Parameterize Azure Data Factory Pipelines
- Add Data Validation Checks
- Integrate Azure Key Vault
- Enable Pipeline Monitoring and Logging
- Implement CI/CD using Azure DevOps

---
