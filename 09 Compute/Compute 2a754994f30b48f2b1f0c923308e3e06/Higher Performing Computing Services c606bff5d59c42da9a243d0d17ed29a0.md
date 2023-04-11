# Higher Performing Computing Services

# The Nitro System

The Nitro System is a combination of dedicated hardware and lightweight hypervisor for faster computing and enhanced security

All EC2 instances use the Nitro System

- Nitro Card - specialised card for VPC, EBS
- Nitro Security Chips - Integrated into the motherboard, protects hardware resources
- Nitro hypervisor - lightweight, Memory and CPU allocation with Bare Metal performance

# Bare Metal Instance

Launch an EC2 instance with no hypervisor, so you can run workloads directly on the hardware for maximum performance.

M5 and R5 EC2 instances run bare metal

# Bottlerocket

Linux-based OS purpose-built for running containers on VMs and bare metal hosts

# AWS ParallelCluster

### What is HPC?

<aside>
⚠️ HPC is hundreds of thousands of servers with fast connections between them with the purpose of boosting computing capacity.

</aside>

When you need a supercomputer to perform computations too large or too slow to run on a standard computer.

Basically ML, or VERY complex other stuff

AWS ParallelCluster is an open-source cluster management tool that makes it easy to deploy and manage HPC clusters on AWS.