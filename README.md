# Wakwetu Automated Cloud ROI & Governance Pipeline (FinOps)

## 📌 Project Overview
An enterprise-grade serverless data lakehouse designed to ingest, transform, and visualize AWS Cloud expenditures. This project demonstrates the shift from reactive accounting to proactive cloud governance (FinOps).

## 🏗️ Architecture
- **Storage:** Amazon S3 (CUR 2.0 Parquet Exports)
- **Cataloging:** AWS Glue Crawler & Data Catalog
- **Analytics:** Amazon Athena (SQL-92)
- **Visualization:** Amazon QuickSight (Direct Query Mode)



## 🛠️ Repository Structure
- `01-Architecture/`: Design specifications and technical decision logs.
- `02-Governance/`: Project Charter and official Closure Reports.
- `03-Scripts/`: Optimized SQL templates for cost analysis.
- `04-Artifacts/`: Visual evidence, dashboards, and PDF reports.

## 🚀 Technical Highlights
- **Serverless Scaling:** Zero-infrastructure management using Glue and Athena.
- **Cost Optimization:** Leveraged Parquet columnar storage to reduce query costs by ~90%.
- **Governance:** Implemented deterministic SQL filters to isolate unblended costs and remove metadata noise.
