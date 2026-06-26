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
User
  |
Application Load Balancer
  |
EC2 Auto Scaling Group
  |
RDS MySQL Database

Additional Services:
- S3 for backup storage
- CloudWatch for monitoring
- CloudTrail for auditing

## Purpose
The purpose of this project is to design a secure, highly available, and scalable …
