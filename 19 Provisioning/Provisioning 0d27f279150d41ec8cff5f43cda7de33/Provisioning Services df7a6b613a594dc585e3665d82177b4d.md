# Provisioning Services

<aside>
⚠️ Provisioning is the allocation or creation of resources and services for the customer

</aside>

AWS Provisioning Services set up AWS Services

Most of them just use CloudFormantion (CFN) underneath

# Elastic Beanstalk (EB)

**PaaS to easily deploy Web-apps**

EB will provision EC2, S3,  SNS, CloudWatch, Auto Scaling Group, LBs

Like Heroku

# AWS OpsWorks

**Config management service**

Provides managed instances of **Chef** and **Puppet**

“I want to have a LB, serves etc.” and it will provide them indirectly

# CloudFormation

**Infra modelling and provisioning service**

IaC

Automatically provision services using templates in JSON or YAML files

# AWS QuickStarts

Pre-made packages to launch and configure infra

Basically **CFN templates authored by AWS or the community**

# AWS Marketplace

**Digital catalogue of thousands of software** listings from software vendors

# AWS Amplify

Mobile and web-app framework, specifically for serverless services - DynamoDB, API Gateway etc

Will provision your AWS service backend

# AWS App Runner

**PaaS but for containers**

Service allows to deploy containerised web apps and APIs at scale

# AWS Copilot

CLI to launch and manage containerised apps on AWS

# AWS CodeStar

Unified UI for managing software development in one place.

Project templates

Easily launch stacks like LAMP (LAMP is an acronym for the operating system, Linux; the web server, Apache; the database server, MySQL; and the programming language, PHP)

# AWS Cloud Development Kit (CDK)

IaC

Allows to use code to generate CFN templates