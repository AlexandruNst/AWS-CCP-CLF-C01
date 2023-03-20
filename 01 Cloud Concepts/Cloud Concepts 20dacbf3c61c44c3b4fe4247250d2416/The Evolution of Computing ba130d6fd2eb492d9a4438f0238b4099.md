# The Evolution of Computing

A CSP has multiple offerings, and you have to choose one that meets your use case

### Dedicated

---

![Untitled](The%20Evolution%20of%20Computing%20ba130d6fd2eb492d9a4438f0238b4099/Untitled.png)

- A physical server **utilised by a single customer**
- Single-node clusters, bare metal machines
- You have to guess capacity, and will overpay for underutilised server
- No vertical scaling (maybe just more memory one that one machine)
- Limited by the OS
- Guarantee of security, privacy, utility of all resources

### VMs

---

![Untitled](The%20Evolution%20of%20Computing%20ba130d6fd2eb492d9a4438f0238b4099/Untitled%201.png)

- **Multiple VMs on one machine**
- Hypervisor in the software that lets you run the VMs
- A physical server shared by multiple customers
- Can pay for fraction of server, but there will still be underutilisation
- Limited by OS, Resource conflicts
- Easy to vertical and horizontal scale

### Containers

---

![Untitled](The%20Evolution%20of%20Computing%20ba130d6fd2eb492d9a4438f0238b4099/Untitled%202.png)

- VM running **multiple containers**
- Uses a Docker Deamon to allow to run multiple containers
- Can choose the capacity that is more cost-effective
- Will not cause resource sharing conflicts

### Functions

---

![Untitled](The%20Evolution%20of%20Computing%20ba130d6fd2eb492d9a4438f0238b4099/Untitled%203.png)

- Knows as ************************************Serverless Compute************************************
- You upload code, choose memory and duration
- Not care about OS, you just know you wanna run Ruby or Python or Node
- Only responsible for code and data
- Very cost-effective, only pay for the time the code is running, VMs only run when there’s code to be executed