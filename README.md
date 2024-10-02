# Data Engineering YouTube Analysis project

### Overview
This project focuses on the secure management, organization, and analysis of structured and semi-structured data from YouTube videos, based on video categories and trending metrics.

### Project Objectives
1. Data Ingestion — Establish a system to efficiently ingest data from various sources.
2. ETL Pipeline — Process raw data, transforming it into a structured and usable format.
3. Data Lake — Centralize data storage by integrating data from multiple sources into a single repository.
4. Scalability — Ensure the system can handle the increasing volume of data as it grows.
5. Cloud Integration — Utilize cloud services to handle large datasets beyond the capacity of local machines. AWS will be our chosen cloud platform.
6. Reporting — Develop a dashboard to provide insights and answer predefined business questions.

### AWS Services Utilized
1. Amazon S3 — Scalable object storage service offering data availability, security, and high performance.
2. AWS IAM — Secure identity and access management for controlling access to AWS resources.
3. Amazon QuickSight — A serverless, scalable business intelligence (BI) tool for data visualization and reporting.
4. AWS Glue — A serverless service to simplify data discovery, preparation, and integration for analytics.
5. AWS Lambda — Serverless computing service that runs code in response to events without the need for server management.
6. AWS Athena — Interactive query service allowing direct data querying from Amazon S3 without the need for loading the data.

### Dataset Details
The dataset, sourced from Kaggle, contains statistics (in CSV format) on daily trending YouTube videos across various regions. Up to 200 trending videos are recorded per day for each location, including details like video title, channel name, publication time, tags, views, likes, dislikes, description, and comment count. Additionally, a category ID unique to each region is provided via a JSON file.

Dataset link: https://www.kaggle.com/datasets/datasnaek/youtube-new
