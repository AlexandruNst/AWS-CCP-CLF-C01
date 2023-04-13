# Elastic Beanstalk (EB)

PaaS = build apps without having to maintain the infrastructure

EB is a PaaS for **deploying web-apps with little to no knowledge of the infrastructure**

So you can focus on the code, and not on setting up deployment pipelines and DevOps

Choose a platform, upload your code, done.

Not recommended for **Production** apps (in large companies. small it work out great)

Powered by CFN, sets up

- LB
- ASG
- RDS db
- EC2 (preconfigured or custom)
- CloudWatch (monitoring), SNS
- Blue/Green deployment methodology
- Security
- **Can run Dockerised environments**

![Untitled](Elastic%20Beanstalk%20(EB)%20c2e7334b12e744999f42fcfed75cd98f/Untitled.png)