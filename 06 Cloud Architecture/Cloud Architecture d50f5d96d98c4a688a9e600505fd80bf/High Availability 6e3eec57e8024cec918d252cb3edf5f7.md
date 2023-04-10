# High Availability

<aside>
⚠️ Ability for your service to **remain available** by ensuring there is **no single point of failure** and a certain level of performance

</aside>

In AWS, to ensure HA you **run the workload on multiple AZs (3)**

If 1 or 2 become unavailable, your service remains available

![Untitled](High%20Availability%206e3eec57e8024cec918d252cb3edf5f7/Untitled.png)

In order to accomplish that, we use a **Load Balancer**

## Elastic Load Balancer

<aside>
⚠️ A LB allows to evenly distribute the traffic to multiple servers, in 1 or more datacenters. If a server/datacenter becomes unavailable, the LB will route only to available ones.

</aside>

You need to spread the workload on 2, 3 or more AZs depending on demand.