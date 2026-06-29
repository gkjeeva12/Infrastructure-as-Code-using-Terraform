# Infrastructure as Code (IaC) using Terraform

## 📌 Project Overview

This project demonstrates **Infrastructure as Code (IaC)** using **Terraform** to automate the provisioning and management of AWS infrastructure. Instead of creating resources manually through the AWS Console, Terraform creates and manages them using code.

## 🎯 Objectives

* Automate AWS infrastructure deployment.
* Reduce manual configuration errors.
* Enable reusable and version-controlled infrastructure.
* Understand the Terraform workflow.

## 🛠️ Technologies Used

* Terraform
* Amazon Web Services (AWS)
* Git & GitHub
* Visual Studio Code
* AWS CLI

## 🏗️ AWS Resources Created

* Virtual Private Cloud (VPC)
* Public Subnet
* Internet Gateway
* Route Table
* Security Group
* EC2 Instance
* S3 Bucket

## 📂 Project Structure

```text
Terraform_Project/
├── main.tf
├── provider.tf
├── variables.tf
├── outputs.tf
├── terraform.tfvars
├── .gitignore
└── README.md
```

## 🔄 Terraform Workflow

### Initialize Terraform

```bash
terraform init
```

### Validate Configuration

```bash
terraform validate
```

### Preview Changes

```bash
terraform plan
```

### Create Infrastructure

```bash
terraform apply
```

### Destroy Infrastructure

```bash
terraform destroy
```

## 📸 Screenshots

Add screenshots of:

## Terraform Init
![Terraform Init](screenshots/terraform init.png)

## Terraform Plan
![Terraform Plan](screenshots/terraform plan.png)

## 📈 Learning Outcomes

* Learned Infrastructure as Code (IaC) concepts.
* Automated AWS resource provisioning using Terraform.
* Managed infrastructure using code.
* Understood the complete Terraform lifecycle.

## 🏁 Conclusion

This project successfully demonstrates how Terraform can be used to automate AWS infrastructure deployment, making cloud resource management faster, consistent, and more efficient.
