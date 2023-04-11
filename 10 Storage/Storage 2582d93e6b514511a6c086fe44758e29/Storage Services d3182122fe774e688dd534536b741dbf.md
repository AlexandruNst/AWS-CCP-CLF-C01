# Storage Services

### Simple Storage Service (S3)

**Serverless object storage service**

Upload very large files, unlimited number of files

Pay for what you store

### S3 Glacier

**Cold storage service**

Low cost storage for archiving and long-term backup

Uses previous generation HDD drives to achieve low cost

Secure and durable

### Elastic Block Store (EBS)

**Persistent block storage service**

Virtual hard drive in the cloud, to be attached to an EC2 instance

Can be set up from the EC2 Console

Must be in the same AZ as EC2

![Untitled](Storage%20Services%20d3182122fe774e688dd534536b741dbf/Untitled.png)

![Untitled](Storage%20Services%20d3182122fe774e688dd534536b741dbf/Untitled%201.png)

Choose between SSD, IOPS SSD, Throughput HDD, Cold HDD

![Untitled](Storage%20Services%20d3182122fe774e688dd534536b741dbf/Untitled%202.png)

### Elastic File Storage (EFS)

**Cloud-native NFS file system service**

Storage you can mount to multiple EC2’s at the same time

**When you need to share files between multiple servers**

Serverless - just care about what you store and consume, pay for what you store

### Storage Gateway

**Hybrid cloud storage**

Extends on-prem storage to cloud

1. File Gateway - extends local storage to S3
2. Volume Gateway - caches local drives to S3 for continuous backup in cloud
3. Tape Gateway - stores files on virtual tapes for backup. Very cost effective, long term

### AWS Snow Family

**Storage devices used to physically migrate large amounts of data to cloud**

![Untitled](Storage%20Services%20d3182122fe774e688dd534536b741dbf/Untitled%203.png)

1. Snowcone - small snowball, 8TB
2. Snowball Edge - briefcase sized, 50-80 TB
3. Snowmobile - cargo container transported on a truck, 100PB

![Untitled](Storage%20Services%20d3182122fe774e688dd534536b741dbf/Untitled%204.png)

Amazon OpsHub - GUI for managing snow devices

**ONLY IN US**

### AWS Backup

**Fully managed backup service**

Easy to centralize and automate backup of data across multiple services: EC2, RDS, EBS, DynamoDB, EFS, Storage Gateway

### CloudEndure Disaster Recovery

Continuously replicates data in a low-cost staging area in preferred region, enabling fast recovery in case of failures

### Amazon FSx

Feature rich and high-performant file system

1. FSx for Window File Server
    - Uses SMB protocol, allows to mount FSx to Windows servers
2. FSx for Lustre
    - Uses Linux’s Lustre file system, allows to mount FSx to Linux Servers