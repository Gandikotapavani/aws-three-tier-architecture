
AWS Three-Tier Web Application Architecture using VPC, EC2, Application Load Balancer and Amazon RDS.

# AWS Three-Tier Web Application Architecture

## Project Overview

This project demonstrates the design of a secure and scalable Three-Tier Web Application Architecture using Amazon Web Services (AWS).

The architecture separates the application into three layers: Presentation Tier, Application Tier, and Database Tier.

## AWS Services Used

- Amazon VPC
- Public and Private Subnets
- Internet Gateway
- Route Tables
- Application Load Balancer (ALB)
- Amazon EC2
- Amazon RDS
- Security Groups
- AWS IAM

## Architecture

### 1. Presentation Tier
- Receives incoming user requests.
- Uses an Application Load Balancer.
- Distributes traffic to application servers.

### 2. Application Tier
- Runs application logic using Amazon EC2.
- Hosted in private subnets.
- Receives traffic only from the load balancer.

### 3. Database Tier
- Uses Amazon RDS.
- Stores application data securely.
- Allows database access only from the application tier.

## Request Flow

User → Application Load Balancer → EC2 Application Server → Amazon RDS

## Security Implementation

- Network isolation using VPC.
- Public and private subnet separation.
- Security Groups for traffic control.
- Database access restricted to application servers.
- IAM permissions following least privilege.

## Project Objectives

- Understand AWS networking fundamentals.
- Implement three-tier architecture concepts.
- Learn secure communication between AWS resources.
- Understand scalability and high availability.
- Gain practical AWS Cloud architecture knowledge.

## Future Enhancements

- Infrastructure as Code using Terraform.
- Auto Scaling Group.
- CloudWatch monitoring.
- CI/CD pipeline using Jenkins.
- Docker integration.

## Author

Pavani Gandikota

B.Tech Information Technology | 2027 Batch

Interested in AWS Cloud and DevOps Engineering.
