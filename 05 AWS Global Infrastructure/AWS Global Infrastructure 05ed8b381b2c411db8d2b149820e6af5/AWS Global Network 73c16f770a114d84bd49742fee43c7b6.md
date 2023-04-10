# AWS Global Network

<aside>
⚠️ The **interconnections between AWS Global Infrastructures**.

</aside>

![Untitled](AWS%20Global%20Network%2073c16f770a114d84bd49742fee43c7b6/Untitled.png)

~ like a private expressway, where things can move fast between datacenters

## Edge Locations

<aside>
⚠️ Are **on and off ramps** to the AWS Global Network

</aside>

### On Ramps

These are used by services like 

- AWS Global Accelerator
    
    (Route traffic to your applications using the AWS global network instead of the internet)
    
- AWS S3 Transfer Acceleration
    
    (Transfer Acceleration leverages Amazon’s CloudFront’s globally distributed edge locations to transfer files quickly)
    

To access AWS resources in other regions **quickly**

### Off Ramps

These are used by services like:

- CloudFront CDN

To provide at the Edge storage and compute near the user.

## VPC Endpoints

<aside>
⚠️ These ensure that the **resources always stay within the AWS Network** and do not traverse over the public Internet.

</aside>

This way if your data doesn’t really need to be publicly available, enforcing it within the AWS Network will make the process much faster.