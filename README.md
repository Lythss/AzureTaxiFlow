# AzurTaxiFlow 🚖🌐

AzurTaxiFlow is a data pipeline project that uses Azure services to ingest, transform, and analyze NYC Taxi data. The pipeline is designed with Azure Data Factory, Synapse Analytics, ADLS Gen2, Power BI, and Purview for secure, efficient data management and insights. 📊🔒

---

## Project Overview 🚀
AzurTaxiFlow is a comprehensive data pipeline built with Azure services to automate the ingestion, transformation, and analysis of NYC Taxi trip data. The solution leverages **Azure Data Factory**, **Azure Synapse Analytics**, **Power BI**, and **Azure Purview** to provide real-time insights into taxi trends, fares, and tips, ensuring data quality and governance. 🔄

---

## Features 🎯
- **Ingestion**: Automates the process of copying raw taxi trip data into Azure Data Lake Storage Gen2 using Azure Data Factory. 🔄
- **Transformation**: Uses Azure Synapse (PySpark or SQL Pool) to clean, enrich, and partition the data. ✨
- **Loading**: Loads the transformed data into a Synapse Dedicated SQL Pool for analysis. 🗂️
- **Analysis**: Builds dashboards and reports using **Power BI** or **Synapse Studio** for actionable insights. 📊
- **Monitoring**: Configures monitoring and alerting for pipeline health and performance using **Azure Monitor** and **Log Analytics**. ⚠️
- **Governance**: Uses **Azure Purview** for data cataloging, lineage, and compliance. 📚
- **Security**: Ensures sensitive data is securely stored using **Azure Key Vault**. 🔒

---

## Setup Instructions ⚙️

### 1. Clone the repository
```bash
git clone https://github.com/your-username/AzurTaxiFlow.git
cd AzurTaxiFlow
