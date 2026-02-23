🚀 Terraform EC2 Reusable Module
📌 Overview
This project demonstrates how to build a reusable Terraform module for provisioning EC2 instances in AWS using Infrastructure as Code (IaC).
Instead of deploying infrastructure manually through the AWS Console, this module allows consistent, repeatable, and automated EC2 deployments across environments.
This reflects real-world DevOps practices where infrastructure is version-controlled and modular.
🛠 Technologies Used
Terraform
AWS EC2
AWS IAM
Security Groups
SSH Key Pairs
🏗 Architecture Concept
The module:
Provisions an EC2 instance
Configures security group rules
Accepts variables for AMI, instance type, and tags
Outputs instance ID and public IP
This structure supports reusability across:
Development
Staging
Production environments
📂 Module Structure
main.tf → Defines AWS resources
variables.tf → Defines input parameters
outputs.tf → Exposes useful values
provider.tf → AWS provider configuration
▶️ How to Use
Clone repository
Update variables (region, AMI, instance type)
Run:
terraform init
terraform plan
terraform apply
🎯 Key Learning Outcomes
Writing reusable Terraform modules
Separating configuration from environment variables
Understanding Terraform state management
Applying Infrastructure as Code best practices
