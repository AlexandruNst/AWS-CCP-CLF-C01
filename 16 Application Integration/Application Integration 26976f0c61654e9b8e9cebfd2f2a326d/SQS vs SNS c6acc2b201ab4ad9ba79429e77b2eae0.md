# SQS vs SNS

## TL;DR

SQS and SNS are important components for scalable, large scale, distributed, cloud-based applications:

**SNS** is a distributed **publish-subscribe** service.

**SQS** is distributed **queuing** service.

[AWS — Difference between SQS and SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

# Use Cases

*Choose **SNS** if:*

- You would like to be able to publish and consume batches of messages.
- You would like to allow same message to be processed in multiple ways.
- Multiple subscribers are needed.

*Choose **SQS** if:*

- You need a simple queue with no particular additional requirements.
- Decoupling two applications and allowing parallel asynchronous processing.
- Only one subscriber is needed.

# **Key Differences**

**Entity Type***SQS* : Queue (similar to JMS, MSMQ).*SNS* : Topic-Subscriber (Pub/Sub system).

**Message consumption***SQS* : Pull Mechanism — Consumers poll messages from SQS.*SNS* : Push Mechanism — SNS pushes messages to consumers.

**Persistence***SQS* :
 Messages are persisted for some duration is no consumer available. The 
retention period value is from 1 minute to 14 days. The default is 4 
days.*SNS* : No persistence. Whichever consumer is
 present at the time of message arrival, get the message and the message
 is deleted. If no consumers available then the message is lost.

In SQS the message delivery is guaranteed but in SNS it is not.

**Consumer Type***SQS* : All the consumers are supposed to be identical and hence process the messages in exact same way.*SNS* : All the consumers are (supposed to be) processing the messages in different ways.