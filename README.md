# End-to-End-YouTube-data-analytics-project-using-AWS

## Overview

The objective of this project is to effectively handle, simplify, and analyze structured and semi-structured data from YouTube videos in a secure manner, utilizing video categories and trending metrics.

## Project Goals
1. Data Ingestion — Build a mechanism to ingest data from different sources
2. ETL System — We are getting data in raw format, transforming this data into the proper format
3. Data lake — We will be getting data from multiple sources so we need centralized repo to store them
4. Scalability — As the size of our data increases, we need to make sure our system scales with it
5. Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS


## Services we will be using
1. Amazon S3: Amazon S3 is an object storage service in which data is stored in containers called buckets.
2. AWS IAM: Enables us to manage access to AWS services and resources securely.
3. QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.
4. AWS Glue: A serverless data integration service/ ETL Tool that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
5. AWS Lambda: Lambda is a serverless computing service.
6. AWS Athena: Athena is an interactive query service for S3.

## Dataset Used
The provided Kaggle dataset consists of daily records (CSV files) showcasing the popularity of YouTube videos over an extended period. Each day, numerous locations have up to 200 newly-trending videos, with data for each region stored in separate files. The dataset encompasses various details such as video title, channel title, publication time, tags, views, likes, dislikes, description, and comment count. Additionally, the associated JSON file for each region contains a category_id field, which varies depending on the area.

https://www.kaggle.com/datasets/datasnaek/youtube-new

## Architecture Diagram
<img src="architecture.jpeg">
