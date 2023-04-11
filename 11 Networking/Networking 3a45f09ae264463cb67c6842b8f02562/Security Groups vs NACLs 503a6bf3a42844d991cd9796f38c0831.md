# Security Groups vs NACLs

![Untitled](Security%20Groups%20vs%20NACLs%20503a6bf3a42844d991cd9796f38c0831/Untitled.png)

## Network Access Control Lists (NACLs)

Act as a virtual **firewall at the** **subnet level (not AZ level)**

You create **Allow and Deny rules**

→ Block specific IP addresses known for abuse

## Security Groups

Act as a virtual **firewall at instance level**

**Implicitly deny all traffic**

You **create only Allow rules**

→ Allow an EC2 access on port 22 for SSH

→ **Cannot block a single IP address** (technically can, but have to allow everything else BUT that address which is not feasible) 

Stateful

# Follow along info

1. Security Groups

When setting up an EC2, you automatically get a SG for port 22

In the Security Groups tab in EC2 console, select a security group, click on Edit Inbound Rules

Default Inbound Rule is for 22 i.e. SSH

You can add rules, for e.g. 80 for HTTP

![Untitled](Security%20Groups%20vs%20NACLs%20503a6bf3a42844d991cd9796f38c0831/Untitled%201.png)

**ONLY ALLOW RULES, NO DENY RULES**

1. NACLs

Associated with subnets so find them in VPC Console

When you create your subnet, you get a NACL by default

Click on NACL to edit, Edit Inbound Rules

![Untitled](Security%20Groups%20vs%20NACLs%20503a6bf3a42844d991cd9796f38c0831/Untitled%202.png)

CAN SPECIFY ALLOW/DENY