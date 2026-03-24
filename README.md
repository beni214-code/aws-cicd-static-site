# 🚀 AWS CI/CD Static Website Deployment

A portfolio project demonstrating how to deploy a static website to AWS using **S3, CloudFront, and GitHub Actions** for full CI/CD automation.

---

## 📌 Project Overview

This project showcases how to:

* Host a static website on **Amazon S3**
* Deliver content globally using **CloudFront**
* Automate deployments with **GitHub Actions**
* Structure a clean, production-ready repository

The goal was to move from manual uploads to a fully automated deployment pipeline.

---

## 🧱 Architecture

![Architecture Diagram](images/github-readme-overview.png)

---

## ⚙️ Technologies Used

* **AWS S3** – Static website hosting
* **AWS CloudFront** – CDN for global delivery
* **GitHub Actions** – CI/CD pipeline automation
* **IAM** – Secure deployment permissions
* **HTML/CSS** – Static website

---

## 🔄 CI/CD Pipeline

![GitHub Actions Success](images/github-actions-workflow-success.png)

### Pipeline Flow:

1. Code is pushed to GitHub
2. GitHub Actions workflow is triggered
3. Files are deployed to S3
4. CloudFront cache is refreshed
5. Website updates automatically

---

## 🧭 Project Walkthrough

### 1. Initial Repository Setup

![Initial Commit](images/github-repo-initial-commit.png)

### 2. Files Uploaded to Repository

![Files Uploaded](images/github-repo-files-uploaded.png)

---

### 3. S3 Bucket Created

![S3 Bucket](images/aws-s3-bucket-created.png)

### 4. Files Uploaded to S3

![S3 Upload](images/aws-s3-file-upload-success.png)

### 5. Static Website Hosting Enabled

![S3 Hosting](images/aws-s3-static-hosting-enabled.png)

### 6. Bucket Policy for Public Access

![S3 Policy](images/aws-s3-bucket-policy-public-access.png)

### 7. Website Live via S3 Endpoint

![S3 Live](images/live-site-s3-endpoint.png)

---

### 8. CloudFront Distribution Created

![CloudFront Setup](images/aws-cloudfront-distribution-created.png)

### 9. Website Live via CloudFront (CDN)

![CloudFront Live](images/live-site-cloudfront.png)

---

### 10. IAM User Created

![IAM User](images/aws-iam-user-created.png)

### 11. IAM Policy Configured

![IAM Policy](images/aws-iam-policy-configured.png)

### 12. Access Keys Generated

![IAM Keys](images/aws-iam-access-keys-generated.png)

---

### 13. GitHub Secrets Configured

![Secrets](images/github-actions-secrets-configured.png)

### 14. CI/CD Pipeline Successful Deployment

![Pipeline Success](images/github-actions-workflow-success.png)

---

### 15. Final Deployed Portfolio Site

![Final Site](images/final-portfolio-site.png)

---

## 📂 Repository Structure

```id="repo-structure"
aws-cicd-static-site/
│
├── .github/workflows/   # CI/CD pipeline
├── Site/                # Website files
├── images/              # Project screenshots
├── index.html
├── error.html
└── README.md
```

---

## 🌍 Live Demo

🔗 https://d30my4oz5fzyi0.cloudfront.net

---

## 🎯 Key Learnings

* Built a fully automated deployment pipeline
* Learned how to integrate AWS with GitHub Actions
* Understood CDN behavior and cache invalidation
* Practiced real-world DevOps workflows

---

## 🚀 Future Improvements

* Add custom domain (Route 53)
* Enable HTTPS with ACM
* Add monitoring/logging
* Improve UI/UX design

---

## 👤 Author

**Beni Mulugeta**

Building cloud and DevOps projects while transitioning into a tech career.
