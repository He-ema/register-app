<div align="center">

# 🚀 DevOps CI/CD Project

### **Automated CI/CD Pipeline with AWS, Jenkins, Docker, SonarQube, Kubernetes & Argo CD**

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=36BCF7&center=true&vCenter=true&width=800&lines=DevOps+CI%2FCD+Pipeline;Jenkins+%7C+Docker+%7C+SonarQube;Kubernetes+%7C+AWS+EKS+%7C+Argo+CD;Automated+GitOps+Deployment" alt="Typing SVG" />

<br>

![AWS](https://img.shields.io/badge/AWS-Cloud-orange?style=for-the-badge\&logo=amazonaws)
![Jenkins](https://img.shields.io/badge/Jenkins-CI%2FCD-red?style=for-the-badge\&logo=jenkins)
![Docker](https://img.shields.io/badge/Docker-Containerization-2496ED?style=for-the-badge\&logo=docker)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-326CE5?style=for-the-badge\&logo=kubernetes)
![SonarQube](https://img.shields.io/badge/SonarQube-Code%20Quality-4E9BCD?style=for-the-badge\&logo=sonarqube)
![ArgoCD](https://img.shields.io/badge/ArgoCD-GitOps-EF7B4D?style=for-the-badge\&logo=argo)
![GitHub](https://img.shields.io/badge/GitHub-Source%20Control-181717?style=for-the-badge\&logo=github)

</div>

---

## 🏗️ Project Workflow

![Project Workflow](https://github.com/user-attachments/assets/d270017a-aecc-4a7b-9326-b19fd8b82d84)

---

## ☁️ AWS Infrastructure

The project infrastructure is hosted on AWS.

![AWS Instances](https://github.com/user-attachments/assets/c4960c7a-56e2-462c-845e-b1c242e6d984)

---

## 🔨 Jenkins CI Pipeline

The Jenkins CI pipeline automates the build, testing, SonarQube analysis, Docker image creation, and Docker Hub upload.

![Jenkins CI Pipeline](https://github.com/user-attachments/assets/d108be02-859c-4ffc-8452-3bf585297d87)

---

## 🚢 Jenkins CD Pipeline

The Jenkins CD pipeline handles the continuous deployment workflow.

![Jenkins CD Pipeline](https://github.com/user-attachments/assets/274014af-85d5-4c5c-9975-28b3b549968f)

---

## 🐳 Docker Hub

The application Docker image is built and pushed to Docker Hub as part of the CI pipeline.

![Docker Hub Image](https://github.com/user-attachments/assets/6218f402-4915-4770-b3f8-3a55ed58fef3)

---

## 🔍 SonarQube Analysis

SonarQube is integrated into the CI pipeline to analyze code quality, bugs, vulnerabilities, code smells, and maintainability.

![SonarQube Analysis](https://github.com/user-attachments/assets/fd22f617-7aa1-4d40-96e7-10e81445c785)

---

## 🔄 Argo CD

Argo CD is used for GitOps-based continuous deployment to the Kubernetes cluster.

![ArgoCD Application](https://github.com/user-attachments/assets/f0acf4a2-7f14-4262-a030-cf89f2d316d4)

---

## 🛠️ Technologies

- AWS EC2
- Amazon EKS
- Kubernetes
- Jenkins
- Docker
- Docker Hub
- SonarQube
- Argo CD
- GitHub
- eksctl

---

## 🔁 End-to-End Workflow

```text
Developer
    ↓
GitHub
    ↓
Jenkins CI
    ↓
Build & Test
    ↓
SonarQube
    ↓
Quality Gate
    ↓
Docker Build
    ↓
Docker Hub
    ↓
Jenkins CD
    ↓
Git Repository
    ↓
Argo CD
    ↓
AWS EKS
    ↓
Running Application
