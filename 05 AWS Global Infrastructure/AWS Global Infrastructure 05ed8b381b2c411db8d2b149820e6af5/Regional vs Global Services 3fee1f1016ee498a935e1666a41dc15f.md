# Regional vs. Global Services

## Regional Services

AWS scopes their AWS Management Console on a selected Region

![Untitled](Regional%20vs%20Global%20Services%203fee1f1016ee498a935e1666a41dc15f/Untitled.png)

This determines where an AWS Service will be launched and what will be seen in the Service’s console.

You don’t set the Region for a service at the time of creation (unlike GCP, Azure). The Region will be the one you have selected in the Management Console. You will select the [Subnet](Availability%20Zones%20(AZs)%20c47f208412e9496cb7ee13843be33982.md).

## Global services

Some AWS Services operate across multiple regions

Region will be fixed to *Global*

E.g. S3, CloudFront, Route53, IAM

![Going into the service console changes the region to Global and you can’t change that.](Regional%20vs%20Global%20Services%203fee1f1016ee498a935e1666a41dc15f/Untitled%201.png)

Going into the service console changes the region to Global and you can’t change that.

For Global services you have to select at the time of creation:

- No concept of region (e.g. IAM User, available globally)
- A single region must be explicitly chosen (e.g. S3 Bucket)
    - You select a region but no [AZ](Availability%20Zones%20(AZs)%20c47f208412e9496cb7ee13843be33982.md), because AWS runs the workload in multiple AZs but you don’t have to worry about which one.
- A group of regions / geographical distribution (e.g. CloudFront Distribution) e.g. All world, North America