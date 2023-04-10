# HA Examples in AWS

1. S3 is by default HA because it replicated data in multiple AZs in the region you select when you create it
2. EC2 is a single instance in a single AZ, so you have to manually create additional 2 servers and a LB to balance the traffic
    - you have to **construct** your HA
3. Elastic BeanStalk
    - you can choose (contra cost) to have the service HA
    - does automatically what you need to do for EC2 manually
    - Platform as a Service (PaaS)
    
    ![Untitled](HA%20Examples%20in%20AWS%20e45ba1d46f1147caa5bde21912893f1f/Untitled.png)
    
    ![Untitled](HA%20Examples%20in%20AWS%20e45ba1d46f1147caa5bde21912893f1f/Untitled%201.png)
    
4. RDS
    - Automatically replicates the data in another AZ so it stays HA