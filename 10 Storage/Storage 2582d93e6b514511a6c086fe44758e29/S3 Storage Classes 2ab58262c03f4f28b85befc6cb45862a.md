# S3 Storage Classes

AWS Offers multiple S3 Classes that trade Retrieval Time, Accessibility and Durability for **Cheaper Storage**

![Untitled](S3%20Storage%20Classes%202ab58262c03f4f28b85befc6cb45862a/Untitled.png)

### S3 Standard

Fast! 99.99% Availability, 11 9’s Durability, Replicated on 3 AZs

### S3 Intelligent Tiering

ML determines appropriate, most cost-effective storage class

### S3 Standard-IA (Infrequent Access)

Still Fast! But for retrieval < once a month

Retrieval fee is applied. Reduced Availability.

50% cheaper than Standard

### S3 One-Zone-IA

Still fast as Standard. Data Stored in one AZ. 

Reduced durability - data could get destroyed.

Retrieval fee applied. 20% cheaper than Standard IA

### S3 Glacier

Long-term cold storage.

Retrieval can take minutes to hours.

Very cheap

### S3 Glacier Deep Archive

EXTREMELY cheap

Data retrieval is 12h

There’s also S3 Outposts, but that’s separate storage class

![Untitled](S3%20Storage%20Classes%202ab58262c03f4f28b85befc6cb45862a/Untitled%201.png)

Can also set up so data automatically goes in a glacier after some time to save money

![Untitled](S3%20Storage%20Classes%202ab58262c03f4f28b85befc6cb45862a/Untitled%202.png)

You can even turn S3 into a website hosting service

![Untitled](S3%20Storage%20Classes%202ab58262c03f4f28b85befc6cb45862a/Untitled%203.png)