# Point of Presence (PoP)

<aside>
⚠️ An Intermediate location between an AWS Region and the end user. Could be a datacenter or collection of hardware.

</aside>

In AWS, a PoP is a datacenter **owned by AWS or by a trusted partner** for content delivery or expediated upload.

PoP resources are **Edge Locations** and **Regional Edge Caches**.

Edge Locations - datacenters that hold caches of most popular files closer to the user so that the delivery distance is reduced

Regional Edge Cache/Location - datacenters with much larger caches of less popular files, helps reduce a full round trip and transfer fees

![Untitled](Point%20of%20Presence%20(PoP)%204248cb36d3e6464b89ec29290b301dc0/Untitled.png)

![Untitled](Point%20of%20Presence%20(PoP)%204248cb36d3e6464b89ec29290b301dc0/Untitled%201.png)

## Tier 1 network

A Tier 1 Network is a network that can reach every other network on the Internet **without purchasing IP transit or paying for peering**.

AWS AZs are all connected to multiple Tier-1 transit providers.

## AWS Services using PoPs

AWS Services use PoPs/Edge Locations for **content delivery and expediated upload**.

1. **Amazon CloudFront**
    - Point your website to CloudFront so it will route requests to the nearest Edge Location cache
    - You can choose an origin for the cache (web-server or storage)
    - Caches the content of origin in various Edge Locations around the world
2. **Amazon S3 Transfer Acceleration**
    - Generate a special URL that can be used by users to upload files to a nearby Edge Location.
    - Once there, it can move much faster across the AWS Network to the S3
3. **AWS Global Accelerator**
    - Find the optimal path between a user and the web-server
    - Deployed within Edge Locations, so you send user traffic to an Edge Location instead of your web application.
    - Great when your server is in a region and you don’t have infrastructure in other regions