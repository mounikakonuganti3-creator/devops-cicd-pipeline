# Automated CI/CD Pipeline for Containerized Applications

## Project Overview
This project demonstrates a complete CI/CD workflow using GitHub Actions, Docker, Kubernetes, and Terraform.

## Tools Used
- GitHub Actions
- Docker
- Kubernetes
- Terraform
- AWS
- Linux

## Project Structure

devops-cicd-pipeline/
├── Dockerfile
├── Jenkinsfile
├── terraform/
├── kubernetes/
├── .github/workflows/
└── README.md


## Pipeline Workflow

Code Commit
↓
GitHub Actions
↓
Build Docker Image
↓
Push Image
↓
Deploy to Kubernetes
↓
Application Running

