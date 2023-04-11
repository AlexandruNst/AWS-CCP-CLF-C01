# VPCs & Subnets

<aside>
⚠️ a VPC is a logically isolated section of the AWS Network where you launch AWS resources.

</aside>

Spans all AZs in a region

You choose a range of IPs using CIDR Range ([don’t even try](https://youtube.com/watch?v=iDiGBIOq7ec&feature=shares))

CIDR Range of 10.0.0.0/16 = 65,536 IP Adresses

![Untitled](VPCs%20&%20Subnets%20a2b997c4659e45f3b41ef314a00f95ee/Untitled.png)

<aside>
⚠️ Subnets are logical partitions of an IP network into multiple smaller network segments

</aside>

You are breaking up your IP range for VPC into smaller networks

Subnets need to have smaller CIDR Range than the VPC

e.g. Subnet CIDR Range 10.0.0.0/24 = 256 IP Adresses

(complex math behind it, just know the bigger the number after /, the lesser the CIDR Range)

![Untitled](VPCs%20&%20Subnets%20a2b997c4659e45f3b41ef314a00f95ee/Untitled%201.png)

1. Public Subnet - can reach the internet
2. Private Subnet - cannot reach the internet
    
    (You need to extra take care though, cus you can for e.g. start an EC2 in your Private Subnet and enable the IP access so it’s not actually private)
    

![Untitled](VPCs%20&%20Subnets%20a2b997c4659e45f3b41ef314a00f95ee/Untitled%202.png)

# Follow a long steps

1. Create VPC - CIDR range
2. Create Subnet in the VPC Console- smaller CIDR range, in an AZ
3. Create an Internet Gateway in the VPC Console
4. Attach IGW to the VPC
5. Go to the Route Tables in VPC Console, Edit Routes
6. Add Route, 0.0.0.0/0, Target: the IGW (???)
7. In the Subnets, Modify Auto-Assign IP address - to auto assign IP address to subnet
8. Now you can launch an EC2 in the subnet

What we’ve achieved? I have no clue :)