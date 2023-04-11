# Follow Along - Elastic IPs, Launch Templates, Auto Scaling Groups (ASGs), Application Load Balancer (ALB)

# AMI

When starting an EC2, you choose an AMI (Linux, Windows etc.)

Each has an ID

ID is **region based**

# EC2 creation

can tick Elastic Inference - for extra GPU for ML

# Elastic IP

you can create an Elastic IP address and attribute that to your EC2 instance.

That IP address does not change

Important when you have services pointing to your server, you need to have a static address for those to point to

![Untitled](Follow%20Along%20-%20Elastic%20IPs,%20Launch%20Templates,%20Auto%2022297ff5cfaf4be886183026c07ddd12/Untitled.png)

# AMI Images

You can create an AMI image based on a server you already created.

You can then use that image to spin servers with the same config

Will also contain all the files!

# Launch Templates

Create a launch template with your AMI

Then go to the templates page, select Launch Instance from Template

Voila

# ASG

Ensures that a single server is running at all times

Increase the capacity if the demand requires it

You create an ASG in the EC2 console and then select an Launch Template (the ASG will use this template to spin up other instances if needed)

![Untitled](Follow%20Along%20-%20Elastic%20IPs,%20Launch%20Templates,%20Auto%2022297ff5cfaf4be886183026c07ddd12/Untitled%201.png)

Create how many min and max instances + desired

![Untitled](Follow%20Along%20-%20Elastic%20IPs,%20Launch%20Templates,%20Auto%2022297ff5cfaf4be886183026c07ddd12/Untitled%202.png)

condition for when to spin another instance, e.g. 50% CPU utilisation

# ALB

Balances load evenly between instances

![Untitled](Follow%20Along%20-%20Elastic%20IPs,%20Launch%20Templates,%20Auto%2022297ff5cfaf4be886183026c07ddd12/Untitled%203.png)

![Untitled](Follow%20Along%20-%20Elastic%20IPs,%20Launch%20Templates,%20Auto%2022297ff5cfaf4be886183026c07ddd12/Untitled%204.png)

Important to select the same AZs as the ASG

You select a Target Group

- Create a target group for your VPC with some filters
- It will automatically detect the instances that fit those requirements

Then you access your server(s) via the Loadbalancer DNS, you no longer go to the server DNS address directly

i.e. in the URL you type the link to the LB, not the server anymore