# secure-cloud-Infrastructure
## Project Overview
This project creates a secure and scalable cloud infrastructure using AWS CloudFormation. The infrastructure is automatically deployed using a JSON template.

## AWS Services Used
- Amazon VPC
- Internet Gateway
- Public and Private Subnets
- Security Groups
- Amazon EC2
- EC2 Auto Scaling
- Application Load Balancer
- Amazon RDS MySQL
- Amazon S3
- Amazon CloudWatch
- AWS CloudTrail
- AWS IAM
- AWS CloudFormation

## Architecture
Employee Users
                          |
                          |
                    Internet Gateway
                          |
                          |
              Application Load Balancer
                    (Public Subnet)
                          |
          --------------------------------
          |                              |
          |                              |
     EC2 Instance 1                EC2 Instance 2
   (Application Server)        (Auto Scaling Server)
          |
          |
     Employee Management
        Application
          |
          |
     Private Subnet
          |
          |
       RDS MySQL
    (Employee Database)


          |
          |
       Amazon S3
(Employee Documents & Backup)


          |
          |
 CloudWatch + CloudTrail
(Monitoring & Security Audit)

## Purpose
The purpose of this project is to design a secure, highly available, and scalable …
