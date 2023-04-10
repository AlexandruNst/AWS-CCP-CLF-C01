# Availability Zones (AZs)

<aside>
⚠️ An Availability Zone (AZ) is **a physical location made up on one or more datacenters.**

</aside>

<aside>
⚠️ A Datacenter is a **secured building** that contains **hundreds of thousands of computers.**

</aside>

Datacenters within a region will be isolated from each other (different buildings) but will be close enough to provide low latency (<10ms)

It is common to run workloads in 3 AZs to ensure **High Availability** in case 1 or 2 datacenters fail (Regulatory Compliance, hence why AWS puts 3 AZs in each region).

AZs are represented by the region code + a letter identifier

e.g. **us-east-1a**

A **Subnet** is associated with an AZ. You never choose the AZ when  launching resources, you choose the Subnet associated with the AZ.

![Untitled](Availability%20Zones%20(AZs)%20c47f208412e9496cb7ee13843be33982/Untitled.png)

Fun fact: US-EAST-1 has 6 AZs, the most of any region

Example of Architectural Diagram:

![2 Regions. First Region has two AZs associated with/by a Subnet. One has two VMs (EC2) running, the second has one VM.](Availability%20Zones%20(AZs)%20c47f208412e9496cb7ee13843be33982/Untitled%201.png)

2 Regions. First Region has two AZs associated with/by a Subnet. One has two VMs (EC2) running, the second has one VM.