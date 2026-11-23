# AWS Three-Tier Architecture

## Project Overview

This project demonstrates the implementation and understanding of a Three-Tier Web Application Architecture using Amazon Web Services (AWS).

The architecture separates the application into three independent layers: Presentation Tier, Application Tier, and Database Tier to improve security, scalability, and maintainability.

This project was practiced using AWS Skill Builder hands-on learning resources.

## AWS Services Used

- **Amazon VPC:** Creates an isolated virtual network.
- **Public and Private Subnets:** Organizes resources based on accessibility and security requirements.
- **Internet Gateway:** Enables internet connectivity for public resources.
- **Route Tables:** Controls network traffic routing.
- **Amazon EC2:** Hosts application workloads.
- **Application Load Balancer:** Distributes incoming application traffic.
- **Auto Scaling Group:** Automatically adjusts EC2 capacity based on configured scaling policies.
- **Amazon RDS:** Provides managed relational database services.
- **Security Groups:** Controls inbound and outbound traffic.
- **AWS IAM:** Manages access permissions to AWS resources.

## Three-Tier Architecture

### 1. Presentation Tier
- Handles incoming user requests.
- Uses an Application Load Balancer.
- Distributes traffic to application instances.

### 2. Application Tier
- Runs application logic using Amazon EC2.
- Uses private network resources where configured.
- Processes requests received from the load balancer.

### 3. Database Tier
- Uses Amazon RDS to manage relational data.
- Keeps database resources isolated from direct public access.
- Allows authorized application-tier communication.

## Architecture Workflow

1. Users send requests through a web browser.
2. Requests reach the Application Load Balancer.
3. The load balancer forwards requests to EC2 application instances.
4. Application instances communicate with Amazon RDS when database access is required.
5. The application returns responses to users.

## Key Concepts Learned

- AWS VPC networking and subnet configuration.
- Public and private network architecture.
- Internet Gateway and route table configuration.
- EC2 instance management.
- Application Load Balancer configuration.
- Auto Scaling fundamentals.
- Amazon RDS database concepts.
- Security Groups and IAM permissions.
- Multi-tier cloud architecture design.

## Project Objectives

- Understand the design of scalable AWS infrastructure.
- Learn secure communication between application layers.
- Understand load balancing and automatic scaling.
- Gain practical exposure to AWS networking and compute services.

## Learning Platform

AWS Skill Builder – Hands-on Cloud Learning

## Future Enhancements

- Infrastructure as Code using Terraform.
- CI/CD automation using Jenkins.
- Docker containerization.
- CloudWatch monitoring and logging.

## Author

**Pavani Gandikota**

B.Tech – Information Technology | 2027 Batch

Interested in AWS Cloud Computing and DevOps Engineering.
