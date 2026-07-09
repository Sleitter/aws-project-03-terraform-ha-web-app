# Terraform AWS Highly Available Web Application

> Project #3 — Infrastructure as Code with Terraform

## Overview

This project deploys a highly available web application architecture on AWS using Terraform.

The goal is to practice Infrastructure as Code by creating repeatable cloud infrastructure that can be deployed, updated, and destroyed using Terraform.

## Architecture

The architecture includes:

- Amazon VPC
- Public Subnets across two Availability Zones
- Internet Gateway
- Public Route Table
- Application Load Balancer
- Target Group
- Launch Template
- Auto Scaling Group
- Security Groups

## Terraform Files

```text
.
├── providers.tf
├── variables.tf
├── main.tf
├── outputs.tf
├── scripts/
│   └── user_data.sh
├── docs/
├── architecture/
└── screenshots/
```

## How to Deploy

```bash
terraform init
terraform validate
terraform plan
terraform apply
```

## Outputs

```bash
terraform output
```

The main output is the Application Load Balancer DNS name.

## How to Destroy

```bash
terraform destroy
```

## Current Version

**v1.0**

## Author

Lowenskin Santana  
GitHub: https://github.com/Sleitter