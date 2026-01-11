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

###  GitHub Actions – Successful Workflow Run
This screenshot shows the **successful execution** of the GitHub Actions pipeline with all steps completed.

![GitHub Actions Success](https://github.com/user-attachments/assets/7a3bacac-0d03-4747-b7d9-b216d04a9256)

---

###  GitHub Actions Workflow Configuration
This screenshot shows the **workflow YAML file** defining build and deployment steps.

![CI/CD Workflow File](https://github.com/user-attachments/assets/22f81a31-e480-4eee-b252-5f876b48ec5e)

---

##  AWS EC2 Instance (Running)
This screenshot confirms that the **EC2 instance is running** and actively hosting the application.

![AWS EC2 Instance](https://github.com/user-attachments/assets/8f97e253-4d83-4aeb-b4d6-da93357cb576)

---
##  MongoDB Cluster Running
This screenshot confirms that the **MongoDB cluster is active and running**, ensuring the database services are operational and connected to the application.

![MongoDB Cluster Running](https://github.com/user-attachments/assets/5dbdba23-52e1-4c55-9cb6-730fd316f778)

---

##  Security Practices

- AWS account protected using **Multi-Factor Authentication (MFA)**
- Secure access using SSH keys
- Restricted inbound rules via Security Groups

---

##  Outcome

- Fully automated CI/CD pipeline implemented
- Zero manual deployment
- Live production-ready application on AWS
- Industry-standard DevOps practices followed

---

