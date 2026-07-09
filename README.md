# AWS VPC Endpoint for Amazon S3

## 📖 Project Overview

In this hands-on AWS networking project, I configured secure private connectivity between an Amazon EC2 instance and an Amazon S3 bucket using a **Gateway VPC Endpoint**.

The objective was to understand how Amazon S3 traffic can remain within the AWS private network instead of traversing the public internet.

During the implementation, I also encountered an **AccessDenied** error after applying an S3 bucket policy. I investigated the issue, identified a missing VPC Endpoint route table association, corrected the routing configuration, and successfully restored secure access to the S3 bucket.

---

## 🏗️ Architecture

![Architecture](architecture-diagram.png.png)

---

## ☁️ AWS Services Used

- Amazon VPC
- Public Subnet
- Route Table
- Internet Gateway
- Security Group
- Amazon EC2
- Amazon S3
- Gateway VPC Endpoint
- IAM
- AWS CLI

---
