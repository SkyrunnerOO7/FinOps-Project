# FinOps-Project

This repository provides a **DevOps-centric** approach to deploying and managing **AWS Cloud Intelligence Dashboards**, including:

- CUDOS (Cost and Usage Dashboards for Optimization and Savings)
- CID (Cost Intelligence Dashboard)
- KPI (Key Performance Indicators)

These dashboards offer comprehensive insights into AWS cost and usage, facilitating financial accountability, cost optimization, and operational excellence.

---

## 🚀 Overview
![basic_deployment_arch](https://github.com/user-attachments/assets/5c3fd60a-41bd-4c08-bf28-efd963e322f1)

The **Cloud Intelligence Dashboards (CID)** framework is an open-source AWS solution to help customers analyze AWS cost and usage data at scale. Built with best practices from the AWS Well-Architected Framework, these dashboards enable:

- Cost transparency across accounts and services
- Optimization opportunities
- Insights into modernization efforts

---

## 🧰 Features

- **CUDOS Dashboard**: Deep cost visibility with optimization insights
- **CID**: Customizable cost tracking and usage views
- **KPI**: Operational metrics such as Graviton and Spot adoption

---

## 🏗️ Architecture

1. **AWS Cost and Usage Report (CUR)** to Amazon S3 (Management Account)
2. **S3 Replication** to Data Collection Account
3. **AWS Glue & Athena** for querying CUR data
4. **Amazon QuickSight** dashboards with SPICE caching
5. **IAM & Identity Center (SSO)** for access control

---

