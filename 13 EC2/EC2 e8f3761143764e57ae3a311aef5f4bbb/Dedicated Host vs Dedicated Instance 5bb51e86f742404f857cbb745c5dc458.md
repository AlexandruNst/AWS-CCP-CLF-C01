# Dedicated Host vs Dedicated Instance

<aside>
⚠️ Dedicated Hosts are single-tenant EC2 instances, Bring-Your-Own-Licence (BYOL) based on machine characteristics

</aside>

|  | Dedicated Instance | Dedicated Host |
| --- | --- | --- |
| Isolation | Instance isolation | Physical Server isolation |
| Billing | Per instance billing | Per host billing (more) |
| Visibility of physical characteristics | No Visibilities | Sockets, cores, host ID 
(good when a licence is for X cores, Y sockets etc. e.g. Microsoft SQL Server) |
| Affinity between host and instance | No Affinity | The instance can re-start on the same physical server |
| Targeted instance placement | No Control | Control over instance placement on physical server (can specify Host ID) |
| Automatic instance placement | Yes | Yes (possible to not care about the host) |
| Add capacity using allocation request | No | Yes |