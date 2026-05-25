[README.md](https://github.com/user-attachments/files/28202287/README.md)
# Secure AWS Infrastructure

Terraform project for deploying a secure small-business AWS infrastructure foundation.

## Purpose

This project demonstrates cloud engineering, infrastructure as code, networking, IAM awareness, and secure architecture design.

## What This Builds

- VPC
- Public subnet
- Internet gateway
- Route table
- Security group for web traffic
- EC2-ready infrastructure pattern

## Tech Stack

- Terraform
- AWS
- Infrastructure as Code

## Architecture

```text
Internet
   |
Internet Gateway
   |
Public Subnet
   |
EC2 / Web Server Security Group
```

## Setup

Install Terraform and configure AWS credentials first.

```bash
terraform init
terraform plan
terraform apply
```

## Security Notes

This is a learning project. In production, tighten inbound access, avoid broad SSH exposure, use IAM least privilege, centralize logs, and add monitoring.

## Future Enhancements

- Private subnets
- NAT gateway
- Application Load Balancer
- RDS database
- CloudWatch alarms
- SSM Session Manager instead of SSH
- GitHub Actions Terraform pipeline

## What This Demonstrates

- AWS networking
- Terraform fundamentals
- Secure infrastructure planning
- Cloud deployment workflow
