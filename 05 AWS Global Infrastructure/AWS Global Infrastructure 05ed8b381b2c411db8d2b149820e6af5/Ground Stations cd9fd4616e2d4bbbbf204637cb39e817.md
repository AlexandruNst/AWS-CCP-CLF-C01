# Ground Stations

<aside>
⚠️ Lets you control satellite communications without having to worry about building a ground station infrastructure.

</aside>

Use cases could be weather forecasting, surface imaging, comms

How it works:

1. Schedule a Contact - select satellite, start and end time, and the ground location
2. Use the AWS Ground Stations to launch EC2 instances that will uplink and downlink data during the contact, and then put the result data in a S3 bucket

![Untitled](Ground%20Stations%20cd9fd4616e2d4bbbbf204637cb39e817/Untitled.png)