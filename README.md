# YouTube-Analysis-Project-using-AWS

This project is dedicated to building a comprehensive data engineering pipeline for YouTube video analysis using AWS. Our focus is to manage, transform, and analyze data based on video categories and trending metrics to uncover meaningful insights.

## Project Goals

- **Data Ingestion**: Establish a system to ingest raw data from multiple sources into our pipeline.
- **ETL Processes**: Transform the raw data into a structured format suitable for analysis.
- **Data Lake Creation**: Store our data centrally within an AWS S3 data lake to ensure it is both secure and accessible.
- **Scalability**: Ensure that the infrastructure scales seamlessly with the growing dataset size.
- **Cloud Computing**: Utilize AWS services to handle the heavy lifting of data processing tasks.
- **Reporting**: Develop insightful dashboards to visualize the data and inform decision-making.

## AWS Services Utilized

- **Amazon S3**: Our primary data storage solution, handling vast amounts of video data.
- **AWS IAM**: Manages secure access to AWS services and resources.
- **QuickSight**: Provides BI capabilities for creating and managing data visualizations.
- **AWS Glue**: Orchestrates the ETL jobs without the need for server provisioning.
- **AWS Lambda**: Runs code in response to events, facilitating serverless computing.
- **AWS Athena**: Offers interactive query services directly against data in S3.

## Dataset

We use a Kaggle dataset that includes extensive statistics on daily trending YouTube videos, featuring details like video titles, channel information, metrics on views, likes, and comments, and more. This dataset is pivotal in our analysis of trending content on YouTube.

Dataset available at: [Kaggle YouTube Trending Video Dataset](https://www.kaggle.com/datasets/datasnaek/youtube-new)

