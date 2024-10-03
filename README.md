# YouTube Analysis Data Engineering Project

## Overview
This project aims to securely manage, streamline, and perform analysis on structured and semi-structured YouTube videos data based on video categories and trending metrics.

---

## Project Goals
- **Data Ingestion** — Build a mechanism to ingest data from different sources.
- **ETL System** — Transform raw data into the proper format.
- **Data Lake** — Centralize data from multiple sources into a unified repository.
- **Scalability** — Ensure the system can scale with increasing data size.
- **Cloud Integration** — Use cloud services to handle large-scale data processing.
- **Reporting** — Build a dashboard to get insights from the data.

---

## Services Used
- **Amazon S3** — Scalable object storage providing high availability, security, and performance.
- **AWS IAM** — Identity and Access Management for secure access to AWS resources.
- **Amazon QuickSight** — A scalable, serverless, machine learning-powered business intelligence (BI) service for cloud-based data visualization.
- **AWS Glue** — A serverless data integration service that helps discover, prepare, and combine data for analytics and machine learning.
- **AWS Lambda** — A serverless compute service for running code without provisioning or managing servers.
- **Amazon Athena** — An interactive query service for analyzing data in S3 using standard SQL, without data loading.

---

## Dataset
This Kaggle dataset contains statistics on daily trending YouTube videos across different regions. Key data points include:
- **Video title**
- **Channel title**
- **Publication time**
- **Tags, views, likes, and dislikes**
- **Description and comment count**
- **`category_id`** — Differs by region, linked through a JSON file.
- **Dataset Link - https://www.kaggle.com/datasets/datasnaek/youtube-new**

---

