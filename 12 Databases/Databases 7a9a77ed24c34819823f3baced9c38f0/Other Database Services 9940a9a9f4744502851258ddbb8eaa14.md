# Other Database Services

# Redshift

PB size **data warehouse**

Used for analytics, not transactions

Expensive cus it keeps data **hot** - run complex queries on large data very fast

➡️ When you want to generate analytics and reports from large amounts on data

![Untitled](Other%20Database%20Services%209940a9a9f4744502851258ddbb8eaa14/Untitled.png)

# ElastiCache

Managed db using **in-memory and caching** open-source dbs **Redis** and **Memcached**.

➡️ When you need to add a caching layer in front of web server or database

# Neptune

Managed **graph** db.

Data represented as interconnected nodes

➡️ When you need to understand connections between data e.g. Social Media relationships, Fraud Rings

# Amazon Timstreams

Managed **time series** db. 

Think of devices that send lots of time-sensitive data e.g. IoT devices

➡️ When you need to measure how things change over time

# Amazon Quantum Ledger Database

Fully managed **ledger** db

Provides transparent, immutable, cryptographically variable transaction logs

➡️ When you need to record history of financial activities that can be trusted

# Database Migration Service

You can migrate from:

- on-prem to AWS
- from 2 db’s in same or different AWS account using different engines
- from SQL to NoSQL db