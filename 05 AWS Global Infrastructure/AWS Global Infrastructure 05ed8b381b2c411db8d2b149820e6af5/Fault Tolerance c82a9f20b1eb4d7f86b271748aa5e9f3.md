# Fault Tolerance

<aside>
⚠️ A **Fault Domain** is a section of a network that is vulnerable to damage (if a device or system fails). The purpose is that if a failure does occur, **it will NOT cascade outside the domain**, thus limiting the damage.

![Untitled](Fault%20Tolerance%20c82a9f20b1eb4d7f86b271748aa5e9f3/Untitled.png)

</aside>

The scope of a Fault Domain could be:

- Specific servers in a rack
- An entire rack
- An entire room in a datacenter
- The entire datacenter building

AWS defines the boundaries of a domain. On Azure you define the boundaries, AWS abstracts it for you.

<aside>
⚠️ A **Fault Level** is a collection of fault domains.

</aside>

![Untitled](Fault%20Tolerance%20c82a9f20b1eb4d7f86b271748aa5e9f3/Untitled%201.png)

Each Region is designed to be **completely isolated** from other Regions.

Each AZ is **isolated, but connected to other AZs** via low-latency links.

### Failure Zone

In AWS, **Failure Zone** = Fault Domain

Failure Zones:

- physically separated in the metropolitan area
- low flood risk zones
- they have an uninterruptible power supply
- supplied by independent substations to avoid an event on the power grid impact more than one AZ

### Multi-AZ for High Availability

If an app is partitioned across multiple AZs, companies are better protected from power outages, lightning strikes, tornadoes, earthquakes, etc.