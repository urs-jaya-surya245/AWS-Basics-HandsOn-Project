# AWS-Basics-HandsOn-Project
Hands-on AWS project covering EC2, S3, Lambda, and IAM for fresher-level cloud learning
# AWS Basics Hands-On Project

This repository contains hands-on practice projects for core AWS services.

## Services Covered
- EC2 – Launch and manage virtual servers
- S3 – Static website hosting and storage
- Lambda – Basic serverless function
- IAM – Users, roles, and policies

## Tools Used
- AWS Management Console
- AWS CLI
- Python (basic)

## Purpose
To gain practical experience in AWS cloud services and build a fresher-friendly cloud project.

## Author
Jaya Surya Manikala
EC2/ec2-setup.md
## EC2 Instance Setup
- Launched an EC2 instance using Amazon Linux
- Configured security groups to allow HTTP and SSH
- Connected to EC2 using SSH
- Installed Apache web server
Lambda/lambda-function.py
def lambda_handler(event, context):
    return {
        'statusCode': 200,
        'body': 'Hello from AWS Lambda!'
    }
 



