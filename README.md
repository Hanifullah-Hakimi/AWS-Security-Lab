# ☁️ AWS Security Lab

## 📌 Overview

Hands-on AWS security lab focused on Identity and Access Management (IAM), access control, security monitoring, and basic cloud security practices.

This lab demonstrates practical experience securing and investigating AWS resources in a controlled environment using the AWS Management Console, AWS CLI, and Python/Boto3.

## 🛠️ Technologies & Tools

- Amazon Web Services (AWS)
- AWS IAM
- Amazon S3
- AWS CLI
- Python
- Boto3
- CloudTrail
- CloudWatch
- GitHub

## 🔐 Security Skills Practiced

- Identity and Access Management (IAM)
- User and Group Management
- Roles and Policies
- Least Privilege
- Authentication and Authorization
- Access Control
- S3 Security
- Cloud Activity Monitoring
- Security Logging
- Basic Cloud Incident Investigation

## 🧪 Lab Environment

```text
                    AWS Security Lab
                           │
                    AWS Account
                           │
              ┌────────────┴────────────┐
              │                         │
             IAM                       S3
              │                         │
       ┌──────┼──────┐            Bucket Security
       │      │      │
     Users  Groups  Policies
       │
       └──────────────┐
                      │
                Access Control
                      │
             ┌────────┴────────┐
             │                 │
        CloudTrail         CloudWatch
             │                 │
             └────────┬────────┘
                      │
                 Monitoring
