# AWS Cloud Resume Challenge

This is my attempt at cloud resume challenge in AWS.
What is Cloud Resume Challenge? - [The Cloud Resume Challenge](https://cloudresumechallenge.dev/) is a multiple-step resume project which helps build and demonstrate skills fundamental to pursuing a career in Cloud. The project was published by Forrest Brazeal.

---

### **Project Overview: Static Web Hosting on AWS with Terraform & GitHub Actions**

 This comprehensive a multi-series, Infrastructure as Code and CI/CD automation project. It is designed to simplify and accelerate your learning of deploying secure, scalable static websites on AWS using Terraform and GitHub Actions.

You’ll build a complete AWS-based web infrastructure from scratch—covering DNS, SSL, S3 website hosting, and CloudFront CDN—while mastering modular Terraform design and automation practices.

---

### **What You’ll Learn?**

* **Deploy end-to-end AWS infrastructure** using reusable Terraform modules
* **Manage DNS and SSL** with Route 53 and AWS Certificate Manager
* **Host and serve content** from S3 with custom domain support
* **Distribute content globally** using Amazon CloudFront
* **Automate deployments** using GitHub Actions CI/CD pipelines

---

### **Included Terraform Modules**

This project is organized into four core Terraform modules:

1. **S3 Remote Backend** – For state management with Amazon S3 & DynamoDB
2. **DNS & SSL Management** – Using Route 53 and AWS Certificate Manager (ACM)
3. **S3 Static Website Hosting** – Secure and scalable content storage
4. **CloudFront CDN Configuration** – Accelerated content delivery & cache control

---

### **CI/CD Pipeline with GitHub Actions**

You'll implement a GitHub Actions workflow that automates:

* **Infrastructure provisioning** with Terraform
* **Content syncing** to S3 buckets
* **Cache invalidation** on CloudFront

Every time you push a change to your repository, this CI/CD pipeline automatically deploys your infrastructure and syncs the latest content—ensuring your website stays up to date without manual intervention.

---

### **Architecture Diagram**

*A diagram of the complete infrastructure is available in the repository to help visualize how each component connects.*

---

### **Explore the Full Project**

Access the complete source code and documentation on GitHub:
🔗 **[Static Web Hosting on AWS: Terraform Modules & GitHub Actions](#)**

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

