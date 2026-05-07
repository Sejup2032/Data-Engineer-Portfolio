## 👩‍💻 Sejal Patil
### **Data Engineer | Azure & Databricks Specialist**
> *Building scalable Medallion Architectures and Production-Ready Data Platforms.*

<table>
  <tr>
    <td>
      <img width="160" height="210" alt="Sejal Patil" src="https://github.com/user-attachments/assets/bbbbc7ec-4c30-4a77-a564-1c95e32f26f1" style="border-radius: 10px;" />
    </td>
    <td style="padding-left: 25px; vertical-align: middle;">
      <p>
        I am a Data Engineer with 4+ years of experience specializing in cloud-native ecosystem. I build end-to-end pipelines using <b>Azure Data Factory, Databricks, and PySpark</b>.
      </p>
      <p>
        My focus is on <b>DataOps</b>-integrating software engineering best practices like CI/CD, Unit Testing, and Modular Code into the world of Big Data. Currently based in <b>Toronto, Canada</b>.
      </p>
    </td>
  </tr>
</table>

## 🛠 Technical Expertise

| Category | Tools & Technologies |
| :--- | :--- |
| **Cloud & Storage** | ![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white) ![ADLS Gen2](https://img.shields.io/badge/-ADLS%20Gen2-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white) ![Unity Catalog](https://img.shields.io/badge/-Unity%20Catalog-FF3621?style=flat-square&logo=databricks&logoColor=white) |
| **Data Processing** | ![Databricks](https://img.shields.io/badge/-Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white) ![PySpark](https://img.shields.io/badge/-PySpark-E25A1C?style=flat-square&logo=apache-spark&logoColor=white) ![Delta Live Tables](https://img.shields.io/badge/-DLT-FF3621?style=flat-square&logo=databricks&logoColor=white) |
| **Languages** | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/-SQL-00758F?style=flat-square&logo=postgresql&logoColor=white) ![Jinja2](https://img.shields.io/badge/-Jinja2-B41717?style=flat-square&logo=jinja&logoColor=white) |
| **DevOps & BI** | ![ADF](https://img.shields.io/badge/-ADF-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white) ![Logic Apps](https://img.shields.io/badge/-Logic_Apps-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white) ![Asset Bundles](https://img.shields.io/badge/-DABs-FF3621?style=flat-square&logo=databricks&logoColor=white) ![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white) ![Power BI](https://img.shields.io/badge/-Power_BI-F2C811?style=flat-square&logo=power-bi&logoColor=black) |


## 📜 Certifications
- 🔴 **Databricks Certified: Data Engineer Associate**
- 🔵 **Microsoft Certified: Fabric Data Engineer Associate)**
- 🔵 **Google Cloud Certified: Associate Cloud Engineer**
- 🔵 **Microsoft Azure DP-900 & AI-900**
- 🏆 **Databricks Data Privacy & Generative AI Certified**
- 🟢 **HackerRank SQL (Intermediate)**

## 🔹 Projects  
### 🎵 1. End-to-End Azure Lakehouse: Streaming & SCD Type 2 with DLT
*An enterprise-grade platform handling streaming data with historical auditing.*

* **Tech Stack**: 
![Azure Databricks](https://img.shields.io/badge/Azure_Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white) 
![DLT](https://img.shields.io/badge/DLT-FF3621?style=flat-square&logo=databricks&logoColor=white) 
![Asset Bundles](https://img.shields.io/badge/Asset_Bundles-FF3621?style=flat-square&logo=databricks&logoColor=white) 
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apache-spark&logoColor=white) 
![ADLS Gen2](https://img.shields.io/badge/ADLS_Gen2-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white) 
![Jinja2](https://img.shields.io/badge/Jinja2-B41717?style=flat-square&logo=jinja&logoColor=white)
![Unity Catalog](https://img.shields.io/badge/Unity_Catalog-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Logic Apps](https://img.shields.io/badge/-Logic_Apps-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)

* **The Problem**: Schema drift and loss of historical user status during subscription changes.
* **Approach**:
  - Engineered a **Metadata-Driven Ingestion** layer in ADF using a Watermark pattern to handle incremental data loads across multiple tables via `ForEach` loops.
  - Implemented **Delta Live Tables (DLT)** for a declarative Medallion Architecture (Bronze → Silver → Gold).
  - Developed **SCD Type 2** logic for historical tracking and automated quality checks using **DLT Expectations**. Used **DABs** for CI/CD deployment.
  - Integrated **Azure Logic Apps** for automated pipeline failure notifications.

* **Results**:
  - Reduced ingestion compute costs by **45%** by moving from full-load to incremental-load logic.
  - Automated the entire lifecycle from source-extraction to BI-ready Gold tables with zero manual intervention.

* **Code**: [View Repository](https://github.com/Sejup2032/Incremental-ETL-and-Dimensional-Modeling-Platform-on-Azure-Lakehouse-Architecture)
  
### ☁️ 2. Enterprise Azure Data Pipeline (Medallion)
*High-scale batch ingestion and transformation across the Azure Ecosystem.*
* **Tech Stack**: 
![Azure Data Factory](https://img.shields.io/badge/Azure_Data_Factory-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white) 
![Azure Synapse](https://img.shields.io/badge/Azure_Synapse-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white) 
![ADLS Gen2](https://img.shields.io/badge/ADLS_Gen2-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white) 
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apache-spark&logoColor=white) 
![SQL](https://img.shields.io/badge/SQL-003B57?style=flat-square&logo=database&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
* **Highlights**: Designed a modular ingestion framework in ADF; implemented Bronze/Silver/Gold layers in ADLS to improve processing performance by **30%**.
* **Code**: [View Repository](https://github.com/Sejup2032/End-to-end-data-engineering-azure)
---
---

