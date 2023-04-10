# AWS Shared Responsibility Model

<aside>
⚠️ A Cloud Security Framework that defines the security obligations of the customer vs the CSP

</aside>

![Untitled](AWS%20Shared%20Responsibility%20Model%20dab0b4aa9f9c4ef9a866c0bb733e81d6/Untitled.png)

Every CSP has its own variant

Sometimes it varies not only based on the CSP, but also on the type of deployment model or even based on the service category (e.g. Compute, ML, etc)

## In AWS

There are two parties/organisations that are responsible

### Customer

Configuration of Managed Services or Third-Party Software

- Platform (e.g. the OS)
- Applications (e.g. Ruby)
- IAM

Config of Virtual Infra and Systems

- OS
- Networking
- Firewall (Virtual)

Security Config of Data

- Client-Side Data Encryption (e.g. encrypt first before sending local → S3)
- Server-Side Encryption (e.g. turn on encryption on S3)
- Networking Traffic Protection
- Customer Data

### AWS

Everything hardware/Global Infra

- Regions
- AZs
- Edge Locations
- Physical Security

Software/Services

- Compute
- Storage
- Database
- Networking (physical cables, software to set up the routing etc.)

## Another way to look at it…

![Untitled](AWS%20Shared%20Responsibility%20Model%20dab0b4aa9f9c4ef9a866c0bb733e81d6/Untitled%201.png)

Customers are responsible for Security **in** the Cloud

AWS is responsible for Security **of** the Cloud

‼️ Important for Exam

Responsibility in the cloud

If you can configure it or store it, you are responsible for it

Responsibility of the cloud

If you can’t configure it, then the CSP is responsible for it