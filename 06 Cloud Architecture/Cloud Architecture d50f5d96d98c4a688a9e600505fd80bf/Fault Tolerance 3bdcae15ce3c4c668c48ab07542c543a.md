# Fault Tolerance

<aside>
⚠️ Ability to ensure there is **no single point of failure**, thus helping prevent a failure.

</aside>

We can achieve this with **fail-overs**

## Fail-overs

A plan to shift traffic to a redundant server in case the primary system fails.

An example is having a secondary copy of a database that is always synced with the primary and ready to take over (i.e. become the primary db) when a failover occurs

![Untitled](Fault%20Tolerance%203bdcae15ce3c4c668c48ab07542c543a/Untitled.png)

In AWS we achieve this using:

## RDS Multi-AZ

Run a duplicate standby db in another AZ, ready for fail-over