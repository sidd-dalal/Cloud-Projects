# Cloud Computing Projects and Resources

This repository contains a collection of cloud computing projects focusing on AWS services. Each project demonstrates the implementation of specific AWS components and concepts to build secure, scalable, and resilient cloud infrastructure.

## Projects

### Project 1: Understanding NACLs and Security Groups
- **Description**: This project focuses on understanding and configuring Network Access Control Lists (NACLs) and Security Groups in AWS. These components are essential for managing traffic at the subnet and instance levels, ensuring network security and control.
- **Key Components**:
  - Configuring Security Groups for instances
  - Setting up NACLs for subnet-level traffic control
  - Testing and validating inbound/outbound traffic rules
- **Link**: [Project 1: Understanding NACLs and Security Groups](https://github.com/sidd-dalal/cloud/blob/main/Project1%3AVPC/README.md)

---

### Project 2: Highly Available VPC for Production
- **Description**: This project demonstrates how to create a production-ready Virtual Private Cloud (VPC) with high availability. It includes deploying servers across two Availability Zones using an Auto Scaling group and Application Load Balancer for improved resiliency. The servers are hosted in private subnets, connected to the internet via a NAT gateway, which is also deployed in multiple Availability Zones for redundancy.
- **Key Components**:
  - VPC creation with public and private subnets
  - Application Load Balancer and Auto Scaling group
  - NAT Gateway in multiple Availability Zones
  - Enhanced resiliency and security
- **Link**: [Project 2: Highly Available VPC for Production](https://github.com/sidd-dalal/cloud/blob/main/Project2/README.md)

---

### Project 3: Hosting a Static Website on S3
- **Description**: This project involves hosting a static website on an S3 bucket. The bucket is configured for website hosting, with public access settings and optional versioning or lifecycle policies to manage website files efficiently.
- **Key Components**:
  - S3 bucket setup for static website hosting
  - Configuring public access and permissions
  - Optional: Versioning and lifecycle policies
- **Link**: [Project 3: Hosting a Static Website on S3](https://github.com/sidd-dalal/cloud/blob/main/Project3%3AS3/README.md)

---

## Technologies Used
- **Cloud Provider**: Amazon Web Services (AWS)
- **Configuration Tools**: AWS Management Console, AWS CLI
- **Scripting**: Bash

---
