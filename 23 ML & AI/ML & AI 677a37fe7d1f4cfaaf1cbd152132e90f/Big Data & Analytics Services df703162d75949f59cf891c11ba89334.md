# Big Data & Analytics Services

### Big Data?

Massive volumes of structured/unstructured data that is so large, it is difficult to move and process using traditional db and software techniques

Good luck :)

# Amazon Athena

Serverless interactive query service

Takes CSV or JSON files from an S3 bucket and loads them in temporary SQL tables so you can run SQL queries

➡️ **When you want to query CSV and JSON files**

# Amazon CloudSearch

Full-text search service

➡️ When you want to add search to your website

# Amazon Elasticsearch Service (ES)

Managed Elasticsearch cluster

Elasticsearch is a open-source full-text search engine

More robust than CloudSearch but requires more servers and maintenance

# Amazon Elastic MapReduce (EMR)

Data processing and analysis using MapReduce

➡️ When needing to transform unstructured data into structured data on the fly

Leverages open-source tech like Spark, Hive, Pig

# Kinesis Data Streams

Real-time streaming data service

Create Producers who send data to the stream

Multiple consumers can then consume the data

➡️ When doing real-time analytics, data from fleet of IoT devices

# Kinesis Firehose

Serverless version of Kinesis Data Streams.

Pay-on-demand for the data consumed in the stream, don’t worry about underlying servers

# Amazon Kinesis Data Analytics

Allows to run queries against data flowing through the real-time stream

Create reports and analysis on the data

# Amazon Kinesis Video Streams

Analyse and process real-time streaming videos

# Managed Kafka Service (MSK, yea :))

Managed Apache Kafka Service

Kafka is for creating real-time streaming data pipelines

Similar to Kinesis but more robust

# Redshift

PB size data warehouse

➡️ When you want analytics and reports from a large amount of data

# Amazon QuickSight

Business Intelligence (BI) Dashboard

Like Tableau but for AWS

Business dashboards with little to no programming knowledge, ingests multiple types of dbs

# AWS Data Pipeline

Automates the movement of data

Reliably move data between compute and storage services

# AWS Glue

ETL service 😍

Move data from one location to another, perform transformations before reaching the final destination

Similar to Data Migration Service (DMS) but more robust

# AWS Lake Formation

A data lake

Centralized and secured repo that stores all your data

Holds vast amounts of raw data in its native format until it is needes

# AWS Data Exchange

Catalogue of third-party datasets. Download, subscribe to, or purchase

e.g. Historical Weather Data

IMDB and Movie data

etc.