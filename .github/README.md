# AWS Cloud Resume Challenge

### **Project Overview: Static Web Hosting on AWS with Terraform & GitHub Actions**

This is my attempt at cloud resume challenge in AWS.
What is Cloud Resume Challenge? - [The Cloud Resume Challenge](https://cloudresumechallenge.dev/) is a multiple-step resume project which helps build and demonstrate your Cloud skills. The project was published by Forrest Brazeal initially.

---
# **Prerequisites**#

Feel free to copy my work,, and make sure that you have the following below steps already done:

* Terraform installed
* AWS CLI installed
* AWS Credentials correctly configured on your machine.
* A domain name, I bought mine from AWS Route53.

---

### **Topics Covered**

* **Deploying end-to-end AWS infrastructure** using reusable Terraform modules
* **Managing DNS and SSL** with Route 53 and AWS Certificate Manager
* **Hosting and serveing content** from S3 with custom domain support
* **Distributing content globally** using Amazon CloudFront
* **Automating deployments** using GitHub Actions CI/CD pipelines

---

### **Included Terraform Modules**

This project is organized into four core Terraform modules:

1. **S3 Remote Backend** – For state management with Amazon S3 & DynamoDB
2. **DNS & SSL Management** – Using Route 53 and AWS Certificate Manager (ACM)
3. **S3 Static Website Hosting** – Secure and scalable content storage
4. **CloudFront CDN Configuration** – Accelerated content delivery & cache control

---

### **CI/CD Pipeline with GitHub Actions**

Implemented a GitHub Actions workflow that automates:

* **Infrastructure provisioning** with Terraform
* **Content syncing** to S3 buckets
* **Cache invalidation** on CloudFront

Every time we push a change to our github repository, this CI/CD pipeline automatically deploys our infrastructure and syncs the latest content—ensuring our website stays up to date without manual intervention.

---

### **Tech Stack**

* **Terraform**
* **GitHub Actions**
* **AWS IAM**
* **Amazon S3**
* **Amazon DynamoDB**
* **AWS ACM (Certificate Manager)**
* **AWS Route 53**
* **Amazon CloudFront**

---

