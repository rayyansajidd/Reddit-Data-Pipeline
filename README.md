# Reddit Data Engineering Pipeline

This project demonstrates a full end-to-end data engineering pipeline that extracts Reddit post data, processes it, and stores it in AWS for further analytics. It combines **Python**, **Apache Airflow**, **Celery**, **PostgreSQL**, and various **AWS services** including **S3**, **Glue**, **Athena**, and **Redshift**.

---

## 📌 Project Objectives

- Automatically extract posts from Reddit
- Store raw data in Amazon S3
- Catalog and transform data using AWS Glue
- Run SQL queries using Athena
- Load curated data into Amazon Redshift
- Orchestrate everything using Apache Airflow and Celery


🛠️ Tech Stack
Python 3.9+

Apache Airflow for scheduling and orchestration

Celery for distributed task execution

PostgreSQL for Airflow metadata

Docker + Docker Compose

AWS S3, Glue, Athena, Redshift


📊 Sample Use Case
Extract Reddit posts from a chosen subreddit

Save raw JSON in S3

Run Glue crawlers to catalog the data

Query using Athena to filter or transform

Store final dataset in Redshift for BI
