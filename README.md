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
```

## 2. Prerequisites ⚙️

- Azure subscription with necessary permissions.
- Azure Synapse, Data Factory, Purview, and Key Vault set up.
- Required SDKs installed for local testing (if needed).

---

## 3. Pipeline Configuration 🔧

- Follow the repository instructions to configure **Azure Data Factory**, **Synapse Analytics**, and **Azure Monitor**.

---

## 4. Run the Pipeline ▶️

- Run the **ADF pipeline** to automate the data ingestion, transformation, and loading processes.
- Visualize the data in **Power BI** or **Synapse Studio** for insights.

---

## Tech Stack 🛠️

- **Azure Data Factory** (ADF) - for data orchestration and pipeline automation 🔄
- **Azure Synapse Analytics** - for data transformation and analytics 📊
  - **Spark Pool** - for distributed data processing 🔥
  - **SQL Pool** - for dedicated data warehousing 🗂️
- **Azure Data Lake Storage Gen2** (ADLS Gen2) - for data storage and management 💾
- **Azure Key Vault** - for securing secrets and credentials 🔐
- **Azure Purview** - for data governance, lineage, and cataloging 📚
- **Power BI** - for data visualization and reporting 📈
- **PySpark** - for data transformation and cleaning (Spark) 🐍

---

## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contact 📬

For any inquiries or issues, feel free to reach out to [Your Name] at [Your Email].

---

## Architecture Diagram 📊
![Architecture Diagram](path-to-your-diagram.png)



