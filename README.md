# Cloud Engineering Academy Project

Greetings and welcome to my Cloud repository! This collection showcases the various projects I've developed and the skills I've refined during my time in the Cloud Engineer Academy.

# Repository Structure 
* cea_cloudformation/ : Contains various CloudFormation templates

# Hands-On Projects Overview
Projects included in this repository:

Auto Scaling Group (ASG) Deployment
  - File: cea-cloudformation/asg.yaml
  - Description: Implements an Auto Scaling Group for dynamic resource management.

EC2 Instance Deployment
- File: cea_cloudformation/ec2.yaml
- Description: Sets up EC2 instances with specified configurations.

IAM Roles and Policies
- File: cea_cloudformation/iam.yaml
- Description: Defines IAM roles and policies for secure access management.

RDS Database Setup
- File: cea_cloudformation/rds.yaml
- Description: Configures a Relational Database Service (RDS) instance.

S3 Bucket Creation
- File: cea_cloudformation/s3-bucket.yaml
- Description: Creates and configures an S3 bucket for storage.

S3 Static Website Hosting
- File: cea_cloudformation/s3-static.yaml
- Description: Sets up an S3 bucket for static website hosting.

VPC Network Configuration
- File: cea_cloudformation/vpc.yaml
- Description: Establishes a Virtual Private Cloud (VPC) with necessary networking components.
- AWS VPC Architecture with Bastion Host
   -This project sets up a secure AWS VPC using CloudFormation with public and private subnets, a bastion host for SSH access, and private application instances.

Key Features
VPC & Subnets: Public for the Bastion Host, private for app instances.

Bastion Host: Secure SSH access to private instances.

Security Groups: Restrict SSH and network access.

Internet Gateway: Public internet access for the Bastion Host only.

Usage
Deploy the CloudFormation template.

SSH into the Bastion Host.

Access private instances securely.
