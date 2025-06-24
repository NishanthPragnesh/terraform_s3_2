# terraform_s3_2

# 🌍 Static Website Hosting using AWS S3 + CloudFront

This project demonstrates how to host a globally accessible static website using **Amazon S3** and **CloudFront**, configured via **Terraform**. It includes logging, HTTPS via CloudFront, and public access setup.

---

## 🏗 Architecture

---![terraform_s3_project2_diagram](https://github.com/user-attachments/assets/6d4598ac-8b66-4130-9ff7-cc09fce5cf95)

## ⚙️ Tech Stack

- 🏗 **AWS Services**: S3, CloudFront, CloudWatch Logs
- 🧩 **IaC**: Terraform
- 🛡 **Security**: IAM roles, public access restrictions
- 🌐 **CDN**: CloudFront for global delivery

---

## 🚀 Live URL

CloudFront URL - "d12qderr3vtjep.cloudfront.net"

(*Custom domain not used due to Free Tier limitations*)

---

## 📝 Setup Instructions

```bash
terraform init
terraform plan
terraform apply

