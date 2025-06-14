# 🧠 AI-Powered Data Pipeline for Warehouse Demand Forecasting

A modular, serverless architecture built on AWS to forecast product demand in real time for warehouse inventory optimisation. This project leverages machine learning and scalable cloud infrastructure to reduce stockouts, overstock, and inefficiencies in supply chains.

---

## 🚀 Project Overview

This solution ingests real-time sales and inventory data, processes it using AWS Glue, and applies an ML model (Amazon SageMaker) to predict future product demand. The results are exposed via a REST API powered by API Gateway and AWS Lambda for integration with external systems.

---

## 🏗️ Architecture Components

- **Data Ingestion:** Amazon Kinesis Firehose → Amazon S3
- **ETL Processing:** AWS Glue triggered by AWS Lambda
- **ML Training & Inference:** Amazon SageMaker (model trained, stored, and deployed)
- **API Layer:** API Gateway → Lambda → SageMaker Endpoint
- **Automation & Monitoring:** EventBridge, CloudWatch, CloudTrail
- **Security:** IAM roles, AWS KMS, VPC with public/private subnets

---

## 📌 Key Features

- Real-time data streaming and transformation
- ML-based demand forecasting with automated retraining
- REST API for predictions
- Modular and reusable infrastructure
- Scalable, fault-tolerant, cost-optimised

---

## 🛠️ Implementation Summary

1. **Kinesis + S3** for data ingestion
2. **AWS Glue + Lambda** for ETL
3. **SageMaker** for training and deployment
4. **API Gateway + Lambda** for predictions
5. **EventBridge** to automate model retraining
6. **CloudWatch & CloudTrail** for monitoring and logging

---

## 📉 Results and Impact

- ⚙️ **25% improvement** in demand forecast accuracy
- 💰 **30% cost savings** using Spot Instances and optimisations
- ⏱️ **40% faster ETL** with AWS Glue and Lambda
- 📈 High scalability and near real-time decision-making
- 🔐 Full-stack AWS security and compliance

---

## 🧩 Reusability

This architecture is industry-agnostic and can be adapted for:
- Retail & E-commerce
- Logistics & Supply Chain
- Financial Forecasting
- Fraud Detection or Personalisation Systems

---

## 📁 Files Included

| File Name                                             | Description                                               |
|-------------------------------------------------------|-----------------------------------------------------------|
| `AI-Powered_Data_Pipeline_Write-Up.docx`              | Full technical documentation                              |
| `Step 1 Data Ingestion Using Terraform and Kinesis.docx` | Guide for initial infrastructure and data ingestion setup |
| `Step 2 Data Processing Using AWS Glue.docx`          | Instructions for data transformation via AWS Glue         |
| `Step 3 Machine Learning with Amazon SageMaker.docx`  | Details on model training and deployment                  |
| `Step 4 Model Integration & Optimisation.docx`        | Integrating the ML model and optimising performance       |
| `Step 5 Deployment & Scaling.docx`                    | Deployment strategies and scaling infrastructure          |
| `AI-Powered_Data_Pipeline_Presentation.pptx`          | Presentation slides for stakeholder/demo walkthrough      |
| `AI-Powered_Data_Pipeline_Presentation.mp4`           | Project demo or narrated walkthrough video                |
| `AI_Pipeline_Video_Walkthrough_Script.docx`           | Narration script for the video demo                       |

---

## 👤 Author

**Tatenda Manyepa**  
AWS Solutions Architect Portfolio Project  
📅 February 2025

---

