# Terraform Assignment: Building EBS and Application Load Balancer Infrastructure

This Terraform project provisions an Elastic Block Store (EBS) and an Application Load Balancer (ALB) infrastructure on AWS. The configuration automates the deployment of these resources, ensuring scalability, reliability, and efficient management.

## Prerequisites
Before running the Terraform scripts, ensure the following:
- Terraform installed 
- AWS CLI installed and configured
- IAM permissions to create resources on AWS
- Access to an AWS account with required services enabled

## Features
- **Elastic Block Store (EBS):** Provides persistent storage for EC2 instances
- **Application Load Balancer (ALB):** Distributes traffic among multiple EC2 instances for improved availability
- **Auto Scaling Group (Optional):** Automatically adjusts the number of instances based on traffic
- **Security Groups:** Ensures access control and network security

# Initialize and Deploy
## Initialize Terraform:
terraform init

## Validate Configuration:
terraform validate

## Plan Deployment:
terraform plan

## Apply Configuration:
terraform apply

## Test the Application:
Use the load balancer URL from the output
Verify that traffic is distributed between instances
## Clean Up:
terraform destroy
