# Capacity Reservations

EC2 instances are backed by hardware, so there is a **finite amount of servers** available within an AZ per instance type or family

You can go launch an EC2 but AWS has ran out of that server!

## Capacity Reservation

A service for EC2 where you **request a reserve of EC2 instance type for a specific Region and AZ**

![Untitled](Capacity%20Reservations%205f4239b851b645b18c085ba0ac440ef1/Untitled.png)

![Untitled](Capacity%20Reservations%205f4239b851b645b18c085ba0ac440ef1/Untitled%201.png)

Can also mention “if you don’t have this exact thing, give me something similar”

The reserved capacity is charged at the selected instance type’s **on-demand rate whether it’s used or not/an instance is running in it or not**

Can use your Regional RI with your Capacity Reservations to benefit from billing discounts