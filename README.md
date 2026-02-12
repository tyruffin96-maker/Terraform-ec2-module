# Terraform EC2 Module (AWS)

## Overview
This project demonstrates building a reusable Terraform module to provision
Amazon EC2 instances in AWS using Infrastructure as Code (IaC).

## What This Module Does
- Provisions an EC2 instance
- Supports configurable AMI, instance type, and key pair
- Applies tags for resource identification
- Outputs instance ID and public IP

## Why Terraform Modules Matter
Terraform modules allow infrastructure to be standardized, reused, and scaled
across environments while reducing configuration drift.

## Project Structure
```text
terraform-ec2-module/
├── main.tf
├── variables.tf
├── outputs.tf
└── modules/ec2/

