# AWS Terraform Docker Kubernetes Deployment

## Project Overview

This project demonstrates the deployment of a containerized NGINX web application using Docker Desktop and Kubernetes, while provisioning AWS infrastructure using Terraform.

The project combines Infrastructure as Code (Terraform), containerization (Docker), and container orchestration (Kubernetes) to simulate a modern cloud-native deployment workflow.

## Architecture

```
Terraform
     │
     ▼
AWS Infrastructure
(Security Group + EC2)

Docker Desktop
     │
     ▼
Docker Image
     │
     ▼
Kubernetes Deployment
     │
     ▼
Kubernetes Service (NodePort)
     │
     ▼
NGINX Web Application
```

## Technologies Used

- AWS EC2
- Terraform
- Docker Desktop
- Docker Engine
- Kubernetes
- kubectl
- NGINX
- Windows PowerShell

## Project Features

- Provision AWS resources using Terraform
- Deploy NGINX using Kubernetes
- Expose application using NodePort Service
- Scale Kubernetes deployment
- Verify Kubernetes cluster resources
- Docker Desktop Kubernetes integration
- Infrastructure managed using Infrastructure as Code (IaC)
