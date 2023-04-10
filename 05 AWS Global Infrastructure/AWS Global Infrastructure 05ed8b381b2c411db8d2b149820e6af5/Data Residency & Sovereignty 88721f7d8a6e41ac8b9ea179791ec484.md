# Data Residency & Sovereignty

<aside>
⚠️ The physical or geographical location of **where an organisation or cloud resources reside.**

</aside>

<aside>
⚠️ **Compliance Boundaries** are a regulatory compliance (legal requirement) by the gov or organisation that describe where the data and cloud resources are allowed to reside.

</aside>

<aside>
⚠️ **Data Sovereignty** is the legal authority that can be asserted over data because its physical location is within jurisdictional boundaries.

</aside>

To strictly define the data residency of data and resources in AWS one can use:

1. **AWS [Outposts**](Outposts%206b5bf1a4fc2a41b8ad2933931ac0e624.md) - physical rack of servers. The data will be there. Quick and simple
2. **AWS Config** - Policy as Code service. Write code to define rules to check the AWS resource config, and alert if they deviate from expectations. Sometimes can auto-remediate.
3. **IAM Policies** - explicitly deny access to specific regions