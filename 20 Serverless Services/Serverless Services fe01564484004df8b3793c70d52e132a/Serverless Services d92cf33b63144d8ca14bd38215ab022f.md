# Serverless Services

### What is serverless

Underlying servers, infra are taken care of by the CSP.

Serverless is generally highly available, scalable and cost-effective

You pay for what you use

# Services

### [DynamoDB](https://www.notion.so/NoSQL-Database-Services-d3b31f0e0e07417eada1c80b4f300659)

Serverless NoSQL key/value an document db

### Simple Storage Service ([S3](https://www.notion.so/S3-75a40af471d445e3a291f2fca63d95d7))

Serverless object storage service

Upload very large and unlimited amounts of files, pay for what you store

Don’t worry about file system, disk upgrades

### ECS Fargate

Serverless container orchestration service.

Same as ECS except you pay-on-demand per running container

(With ECS you have to pay to keep the EC2 running, even if no containers are running)

Don’t worry about underlying server, scaling

### AWS Lambda

Serverless function service

Run code without provisioning servers

Upload code, specify memory and how long before timeout

Charged based on runtime rounded to nearest 100ms

### Step Functions

State machine service

Coordinates multiple services into a serverless workflow

Create logical steps

Make a group of lambdas wait for each other

### Aurora Serverless

Serverless on-demand version of Aurora