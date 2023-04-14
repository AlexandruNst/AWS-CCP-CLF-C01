# Logging Services

# CloudTrail

logs all API calls (SDK, CLI) between AWS Services

Easy and useful to blame

Who created that bucket?

Who spun up that expensive EC2 instance?

# CloudWatch

- CloudWatch Logs - centralized place to store log data
- CloudWatch Metrics - time-ordered set of data points
- CloudWatch Events - trigger an event based on condition e.g. every hour take snapshot of server
- CloudWatch Alarms - triggers notification based on metrics
- CloudWatch Dashboard - create visualisations based on metrics

# AWS X-Ray

Distributed tracing system

Pinpoint issues with microservices

How data moves from one app to another, how long it took to move, if it failed to move tc