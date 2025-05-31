#🛠️ AWS Networking Project with VPC, Load Balancer, NAT Gateway & Auto Scaling

📌 Overview
This project demonstrates a production-like AWS networking setup designed for high availability, scalability, and security. The architecture is implemented using AWS services such as VPC, Subnets, NAT Gateway, Load Balancer, Auto Scaling Group, and Security Groups.

🌐 Architecture Summary

✅ Key Features
🔸 VPC with Subnets
Created a VPC with public and private subnets across two Availability Zones for high availability.

🔸 NAT Gateway & Load Balancer
Deployed NAT Gateways in each public subnet for secure internet access from private subnets.

Configured an Application Load Balancer (ALB) to distribute traffic across EC2 instances.

🔸 Auto Scaling Group
Launched EC2 instances in private subnets using an Auto Scaling Group that automatically scales based on demand.

🔸 Security Groups
Configured Security Groups to control inbound/outbound traffic between ALB, EC2 instances, and the internet.

💡 What I Learned
Designing high-availability VPC architecture

Subnetting and routing concepts

Managing NAT gateway and internet access securely

Load balancing and auto-scaling in AWS

IAM roles and security groups configuration

🔗 Tools & Services Used
AWS VPC

EC2

Auto Scaling Group

Application Load Balancer

NAT Gateway

Subnets (Public & Private)

Security Groups

![Screenshot 2025-05-31 233134](https://github.com/user-attachments/assets/6ad5483d-2a09-4b60-939c-52bb881e91a5)
