# 🚀 End-to-End Azure Data Engineering Pipeline

This project demonstrates the design and implementation of a **cloud-native data pipeline** using Microsoft Azure services. Built with real-world scalability and modularity in mind, this solution follows the **Medallion Architecture (Bronze, Silver, Gold layers)** to ingest, transform, enrich, and visualize large-scale e-commerce data in a modern cloud environment.

## 📦 Dataset Used
The dataset powering this pipeline is the [https://www.kaggle.com/datasets/olistbr/brazilian-ecommerc]([url](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce))e , which contains information on orders made at Olist store — a Brazilian marketplace — from 2016 to 2018.

It includes:
- Customer and seller info
- Order details, reviews, payments
- Geolocation and product categories

This dataset is ideal for building a real-world, multi-layered data pipeline due to its complexity and relational structure.

## 📌 Project Highlights

### ✅ What I Built
- 🏗️ **Architected Medallion Framework** (Raw → Curated → Business-Ready Data)
- 🌐 Ingested data from **HTTP endpoints** and **SQL databases** using **Azure Data Factory (ADF)**
- 🗃️ Configured **ADLS Gen2** storage for data lake management
- 🔁 Built **parameterized and reusable ADF pipelines**
- 🔌 Integrated **MongoDB** for external NoSQL enrichment
- 🧠 Used **Azure Databricks (PySpark)** for data cleaning, joining, and transformation
- 🛠️ Designed **production-grade workflows** with error handling and monitoring
- ⚡ Queried data with **Azure Synapse Analytics**
- 📊 Created **external Gold layer tables** for consumption
- 📈 Built **insightful dashboards** using **Power BI** and **Tableau**

## 💡 Key Learnings
- Designing and scaling **cloud-based data pipelines**
- Managing both **real-time and batch ingestion** strategies
- Working with multiple Azure services in a **cohesive architecture**
- Handling **data lineage**, **monitoring**, and **pipeline parametrization**
- Understanding **cost-efficient** and **high-availability** design principles

## 🔮 Future Work
- Explore **Microsoft Fabric** and **Power BI Embedded**
- Optimize **DAX measures** and create **role-specific dashboards**
- Implement **real-time KPI alerting** via Azure Monitor & Logic Apps
- Automate data storytelling and dynamic dashboard rendering

## 🧰 Tools & Technologies
| Service/Tool          | Purpose                               |
|-----------------------|---------------------------------------|
| Azure Data Factory    | Data orchestration & ingestion        |
| ADLS Gen2             | Scalable cloud storage (Data Lake)    |
| Azure Databricks      | Transformation & enrichment (PySpark) |
| MongoDB               | NoSQL source for enrichment           |
| Azure Synapse         | Analytics & querying layer            |
| Power BI / Tableau    | Data visualization & reporting        |
| SQL                   | Source data & query language          |


