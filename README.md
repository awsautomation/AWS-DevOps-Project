# 🚀 AWS DevOps Project - Terraform Automation

![Terraform](https://img.shields.io/badge/Terraform-IaC-purple?style=for-the-badge&logo=terraform)
![AWS](https://img.shields.io/badge/AWS-Cloud-orange?style=for-the-badge&logo=amazon-aws)
![GitHub](https://img.shields.io/badge/GitHub-CI%2FCD-black?style=for-the-badge&logo=github)
![CI/CD](https://img.shields.io/badge/CI%2FCD-Automation-blue?style=for-the-badge&logo=github-actions)

## 📌 Project Overview
This project automates the deployment of **AWS Infrastructure** using **Terraform**.  
It enables **Infrastructure as Code (IaC)** to manage AWS resources efficiently.  

### 🌟 Key Features:
- ✅ **Fully automated AWS resource provisioning**
- ✅ **Scalable architecture using Terraform modules**
- ✅ **Environment-specific configurations (Dev, Staging, Prod)**
- ✅ **CI/CD pipeline integration for infrastructure deployment**
- ✅ **State management with S3 backend & DynamoDB locking**

---

## 📁 Project Structure
```bash
aws-devops-project/
├── modules/               # Reusable Terraform modules
│   ├── ec2-instance/      # EC2 module
│   ├── vpc/               # VPC module
│   ├── security-groups/   # Security groups module
│   ├── s3/                # S3 module
│   ├── rds/               # RDS module
├── environments/          # Configurations for Dev, Staging, Prod
├── main.tf                # Main Terraform configuration
├── variables.tf           # Input variables
├── outputs.tf             # Output values
├── providers.tf           # AWS provider configuration
├── terraform.tfvars       # Default variable values
├── backend.tf             # S3 backend configuration
├── README.md              # Documentation
├── .gitignore             # Ignore Terraform state files
├── .github/workflows/     # GitHub Actions CI/CD
├── .gitlab-ci.yml         # GitLab CI/CD pipeline
