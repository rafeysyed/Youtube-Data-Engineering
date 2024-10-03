# YouTube Analysis Data Engineering Project
Overview
This project aims to securely manage, streamline, and perform analysis on structured and semi-structured YouTube data based on video categories and trending metrics.

Project Goals
Data Ingestion: Build a mechanism to ingest data from various sources.
ETL System: Transform raw data into a proper format for analysis.
Data Lake: Centralize data from multiple sources into a unified repository.
Scalability: Ensure the system can scale with increasing data volume.
Cloud Integration: Utilize cloud services for handling large-scale data processing.
Reporting: Build a dashboard to answer key business questions.
Services Used
Amazon S3: Provides scalable object storage with high availability, security, and performance.
AWS IAM: Identity and Access Management to securely control access to AWS services and resources.
Amazon QuickSight: A scalable, serverless, machine-learning-powered business intelligence (BI) service for data visualization.
AWS Glue: A serverless data integration service that simplifies discovering, preparing, and combining data for analytics and machine learning.
AWS Lambda: A serverless compute service to run code without managing servers.
Amazon Athena: An interactive query service to analyze data in S3 using standard SQL without data loading.
Dataset
The Kaggle dataset contains statistics on daily trending YouTube videos across various regions. Key attributes include:

Video title
Channel title
Publication time
Tags, views, likes, and dislikes
Description and comment count
category_id field (differs by region, linked via a JSON file)
