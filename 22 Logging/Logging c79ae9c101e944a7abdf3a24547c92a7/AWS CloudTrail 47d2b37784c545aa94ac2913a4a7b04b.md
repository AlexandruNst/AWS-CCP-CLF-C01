# AWS CloudTrail

Very important service

Enables governance, compliance, auditing on your AWS Account

Used to **monitor API calls made on your AWS account**

Easily Identify

- Where - source IP
- When - event time
- Who - User
- What
    - Region
    - Resource
    - Action
    

**Event Record**

![Untitled](AWS%20CloudTrail%2047d2b37784c545aa94ac2913a4a7b04b/Untitled.png)

CloudTrail is logging by default

Will **collect logs for the last 90 days via Event History**

![Untitled](AWS%20CloudTrail%2047d2b37784c545aa94ac2913a4a7b04b/Untitled%201.png)

If you need more than 90 days you need to create a **Trail**

Trails don’t have a GUI and are stored in a bucket

To analyse a trail you need to use **Amazon Athena**