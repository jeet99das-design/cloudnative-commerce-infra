# CloudNative Commerce Infrastructure 🚀

## 📌 Overview

This project demonstrates a complete DevOps pipeline using:

* GitHub Actions (CI/CD)
* Terraform Cloud (Infrastructure as Code)
* AWS (Cloud Provider)

## 🏗️ Architecture

GitHub → Terraform Cloud → AWS

## ⚙️ Features

* Automated infrastructure provisioning
* Secure S3 bucket with:

  * Encryption (AES256)
  * Versioning enabled
  * Public access blocked
* EC2 instance provisioning
* Environment-based configuration

## 🔄 Workflow

1. Code pushed to GitHub
2. GitHub Actions triggers pipeline
3. Terraform Cloud runs plan/apply
4. AWS resources are created automatically

## ☁️ Technologies Used

* Terraform
* AWS (S3, EC2)
* GitHub Actions

## 📸 Output

* S3 Bucket created
* EC2 Instance running

## 🎯 Use Case

This project simulates a real-world platform engineering workflow for managing cloud infrastructure using Infrastructure as Code.
