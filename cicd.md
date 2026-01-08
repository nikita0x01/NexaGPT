#  CI/CD Pipeline & AWS Deployment

This document describes the **CI/CD implementation and AWS deployment** for the NexaGPT project.  
The pipeline automates build, test, and deployment processes using **GitHub Actions** and deploys the application on **AWS EC2**.

---

## CI/CD Overview

- **Source Control:** GitHub
- **CI/CD Tool:** GitHub Actions
- **Deployment Platform:** AWS EC2
- **Automation:** On every push to the main branch
- **Security:** AWS account secured with MFA

---

##  CI/CD Workflow

The CI/CD pipeline performs the following steps:

1. Trigger on push to `main` branch
2. Install dependencies
3. Build the application
4. Deploy to AWS EC2 instance
5. Verify successful deployment

---

##  CI/CD Execution Proof

### 📸 GitHub Actions – Successful Workflow Run
This screenshot shows the **successful execution** of the GitHub Actions pipeline with all steps completed.

![GitHub Actions Success](Screenshot_2026-01-08_211533.png)

---

### 📄 GitHub Actions Workflow Configuration
This screenshot shows the **workflow YAML file** defining build and deployment steps.

![CI/CD Workflow File](Screenshot_2026-01-08_211708.png)

---

## ☁️ AWS Deployment

### 🖥️ AWS EC2 Instance (Running)
This screenshot confirms that the **EC2 instance is running** and actively hosting the application.

![AWS EC2 Instance](Screenshot_2026-01-08_211136.png)

---

### 🌐 Live Application on AWS
This screenshot shows the application **successfully deployed and accessible** via the EC2 public IP.

![Live Application](Screenshot_2026-01-08_212607.png)

---

## 🔐 Security Practices

- AWS account protected using **Multi-Factor Authentication (MFA)**
- Secure access using SSH keys
- Restricted inbound rules via Security Groups

---

## 🎯 Outcome

- Fully automated CI/CD pipeline implemented
- Zero manual deployment
- Live production-ready application on AWS
- Industry-standard DevOps practices followed

---

