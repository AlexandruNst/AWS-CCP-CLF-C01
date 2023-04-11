# Types of Storage Services

Usually all CSPs have 3 types: Block, File, Object

# Elastic Block Store (EBS)

**Block**

Data split into evenly split blocks

Directly accessed by the VM

Supports only a single write volume

→ When you need a virtual hard drive attached to/mounted on a VM

![Untitled](Types%20of%20Storage%20Services%20ee6f8160c0ae4ccdbdd05a32cfa4ed24/Untitled.png)

# AWS Elastic File Storage (EFS)

**File**

File is stored with data and metadata

Multiple connections via network share

Supports multiple reads, writing locks the file

→ When you need a file-share where multiple users or VMs need to access the same drive

![Untitled](Types%20of%20Storage%20Services%20ee6f8160c0ae4ccdbdd05a32cfa4ed24/Untitled%201.png)

# Amazon Simple Storage Service (S3)

**Object**

Object is stored with data, metadata, and unique ID

Scales up well, very little limit

Supports multiple reads and writes with no locks

→ When you just want to upload files, and not worry about the underlying infra. 

→ Not intended for high IOPs (Input-Output per second)

![Untitled](Types%20of%20Storage%20Services%20ee6f8160c0ae4ccdbdd05a32cfa4ed24/Untitled%202.png)