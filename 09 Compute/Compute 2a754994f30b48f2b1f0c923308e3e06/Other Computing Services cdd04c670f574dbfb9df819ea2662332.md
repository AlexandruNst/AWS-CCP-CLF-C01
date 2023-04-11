# Other Computing Services

# Virtual Machines

Emulation of Physical Computer using Software

### Amazon LightSail

- The **managed virtual server service**
- Friendly version of EC2, more beginner friendly, not so much AWS knowledge necessary
- E.g. Launch a Wordpress

# Containers

Virtualising an OS to run multiple workloads on a single OS instance

Used in microservice architecture (divide an app in smaller apps)

### Elastic Container Service (ECS)

- A **container orchestration service** that supports Docker 🐳 containers
- Launches a cluster of server(s) on EC2 instances with Docker installed
- When you need Docker as a Service or to run containers
- When creating:

![Untitled](Other%20Computing%20Services%20cdd04c670f574dbfb9df819ea2662332/Untitled.png)

### Elastic Container Registry (ECR)

- A **repository for container images**
- Has version control

### ECS Fargate

- **Serverless container orchestration service**
- Same as ECS but pay-on-demand per running container
- With ECS you have to keep an EC2 running (and paid for) even with no containers running
- Fargate is kiiiinda *part* of ECS, just if you want the serverless option
- Ticking the below when making a ECS cluster would make it a Fargate Cluster

![Untitled](Other%20Computing%20Services%20cdd04c670f574dbfb9df819ea2662332/Untitled%201.png)

### Elastic Kubernetes Service (EKS)

- A **fully managed Kubernetes service**
- K8 ⛵ is an orchestration software and the standard for managing microservices
- When you need to run Kubernetes as a Service

# Serverless

When the underlying servers are managed by AWS. You don’t have to configure servers

### AWS Lambda

- **Run code without managing servers**
- Upload code, choose memory and how long it is allow the run before timing out
- Charged based on function run time rounded to the nearest 100ms