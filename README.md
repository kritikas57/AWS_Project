# AWS-Based Web Application Deployment Using Application Load Balancer

## Project Overview

This project demonstrates web application deployment on Amazon Web Services (AWS) using EC2 instances and an Application Load Balancer (ALB).

Two EC2 instances were configured to host sample websites (Zomato Clone and Netflix Clone). An Application Load Balancer was used to distribute incoming traffic across the registered instances.

The project provides practical experience with AWS networking, compute services, and load balancing.

## Objectives

- Create and configure a custom VPC.
- Configure public subnets and internet connectivity.
- Launch and configure EC2 instances.
- Deploy sample web applications on EC2.
- Configure an Application Load Balancer.
- Understand Target Groups and traffic distribution.
- Explore AWS Auto Scaling.

## AWS Services Used

| Service | Purpose |
|---|---|
| Amazon VPC | Created a virtual network |
| Amazon EC2 | Hosted web applications |
| Application Load Balancer | Distributed incoming traffic |
| Target Groups | Registered EC2 instances |
| Internet Gateway | Provided internet connectivity |
| Route Tables | Managed network routing |
| Security Groups | Controlled network access |
| Auto Scaling | Explored EC2 scaling |

## Project Architecture

The project consists of a custom VPC with public subnets, two EC2 instances, and an Application Load Balancer.

### Architecture Diagram

![AWS Architecture](architecture/architecture.png)

### Traffic Flow

1. Users send requests through the internet.
2. The Internet Gateway provides connectivity to the VPC.
3. The Application Load Balancer receives incoming requests.
4. The Target Group contains the registered EC2 instances.
5. Traffic is forwarded to the EC2 instances hosting the sample websites.

## Implementation

### 1. VPC Configuration
- Created a custom VPC.
- Configured public subnets.
- Attached an Internet Gateway.
- Configured route tables.

### 2. EC2 Configuration
- Launched two EC2 instances.
- Configured security groups.
- Hosted Zomato and Netflix sample websites.

### 3. Target Group Configuration
- Created a Target Group.
- Registered the EC2 instances.
- Configured health checks.

### 4. Application Load Balancer
- Created an Application Load Balancer.
- Configured listeners.
- Associated the Target Group.
- Accessed the application using the Load Balancer DNS endpoint.

## Project Screenshots

AWS configuration screenshots are available in the `screenshots` folder.

They include:

- VPC configuration
- Public subnet configuration
- Internet Gateway
- EC2 instances
- Target Groups
- Application Load Balancer
- Security Groups

## Technologies Used

- Amazon Web Services (AWS)
- Amazon EC2
- Amazon VPC
- Application Load Balancer
- HTML
- CSS
- JavaScript

## Learning Outcomes

- Practical understanding of AWS infrastructure.
- Experience configuring VPCs and public subnets.
- Understanding EC2 instance deployment.
- Learning Application Load Balancing.
- Understanding Target Groups and health checks.
- Exposure to AWS networking and security.

## Conclusion

This project provided hands-on experience with AWS cloud infrastructure and web application deployment. It demonstrated how an Application Load Balancer can distribute incoming traffic across multiple EC2 instances and helped develop an understanding of fundamental AWS networking and deployment concepts.
