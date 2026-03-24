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

![GitHub Upload Process](images/github-repo-files-uploaded.png)

### Pipeline Flow:

1. Code is pushed to GitHub
2. GitHub Actions workflow is triggered
3. Files are deployed to S3
4. CloudFront cache is refreshed
5. Website updates automatically

---

## 📂 Repository Structure

```
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

🔗 *https://d30my4oz5fzyi0.cloudfront.net*

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

---
