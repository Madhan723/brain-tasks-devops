# Brain Tasks App - DevOps Deployment

## Project Overview

This project demonstrates the deployment of the Brain Tasks React application using a complete DevOps CI/CD workflow on AWS.

The application is:
- Dockerized using Docker
- Stored in Amazon ECR
- Deployed on Amazon EKS
- Automated using AWS CodePipeline and CodeBuild

---

# Application Details

- Application: Brain Tasks React App
- Source Repository: https://github.com/Vennilavanguvi/Brain-Tasks-App
- Deployment Repository: https://github.com/Madhan723/brain-tasks-devops

---

# Technologies Used

- React
- Docker
- Amazon ECR
- Amazon EKS
- AWS CodeBuild
- AWS CodePipeline
- Kubernetes
- NGINX
- GitHub

---

# Project Architecture

```text
GitHub
   ↓
CodePipeline
   ↓
CodeBuild
   ↓
Docker Build
   ↓
Push Image to Amazon ECR
   ↓
Deploy to Amazon EKS using kubectl


