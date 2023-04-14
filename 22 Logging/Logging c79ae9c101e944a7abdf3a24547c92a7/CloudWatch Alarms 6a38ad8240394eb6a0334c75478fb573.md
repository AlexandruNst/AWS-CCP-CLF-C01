# CloudWatch Alarms

**Monitors a Metric based on a defined threshold**

                                                                                 Metric                                         Threshold

![Untitled](CloudWatch%20Alarms%206a38ad8240394eb6a0334c75478fb573/Untitled.png)

When the condition is met, it’s going to **breach an alarm**

Changes state:

- OK - Metric is within threshold
- ALARM - Metric is outside threshold
- INSUFFICIENT_DATA
    - Alarm just started
    - Metric not available
    - Not enough data is available

When state changes, we can define **what action it should trigger**

- Notification
- Auto Scaling Group
- EC2 action

![Untitled](CloudWatch%20Alarms%206a38ad8240394eb6a0334c75478fb573/Untitled%201.png)

Very useful use case - Setting up a billing alarm