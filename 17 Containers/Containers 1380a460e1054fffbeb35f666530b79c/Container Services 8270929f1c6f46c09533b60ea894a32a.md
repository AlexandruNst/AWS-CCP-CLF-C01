# Container Services

# Primary Services

### Elastic Container Service (ECS)

No cold starts - fast starts

Self-managed EC2

![Untitled](Container%20Services%208270929f1c6f46c09533b60ea894a32a/Untitled.png)

### AWS Fargate

Cold starts - starts can be slow

Serverless Containers

More robust than Lambda

AWS-managed EC2

![Untitled](Container%20Services%208270929f1c6f46c09533b60ea894a32a/Untitled%201.png)

![Untitled](Container%20Services%208270929f1c6f46c09533b60ea894a32a/Untitled%202.png)

### Elastic Kubernetes Service (EKS)

Open Source

Runs Kubernetes

![Untitled](Container%20Services%208270929f1c6f46c09533b60ea894a32a/Untitled%203.png)

### AWS Lambda

Only think about the code

Serverless function deployment

Short running tasks

# Provisioning and Deployment

### Elastic Beanstalk (EB)

ECS on training wheels - can deploy ECS for you

PaaS

Works with other app structures other than containers

### App Runner

Overlaps with EB but specialises in containers.

Works **only** with containers

![Untitled](Container%20Services%208270929f1c6f46c09533b60ea894a32a/Untitled%204.png)

### AWS Copilot CLI

![Untitled](Container%20Services%208270929f1c6f46c09533b60ea894a32a/Untitled%205.png)

# Supporting Services

### Elastic Container Registry (ECR)

Repo for Docker images (or any OCI compliant container)

### X-Ray

“It’s distributed tracing” ???

Analyse and debug microservices

### Step Functions

Stitch together Lambdas and ECS tasks to create a state machine