# 🚀 Node.js CI/CD Pipeline with Jenkins, SonarQube, Nexus & Nginx

## 📌 Project Overview
This project demonstrates a complete **CI/CD pipeline** for a **Node.js application** using:
- **Jenkins** for automation
- **SonarQube** for code quality analysis
- **Nexus** for artifact storage
- **Nginx** as a reverse proxy for deployment

The pipeline ensures **code quality, artifact versioning, and automated deployment** for smooth DevOps workflows.

## 📋 Prerequisites
Make sure you have the following installed and configured:

- **Jenkins** with required plugins:
  - Pipeline
  - NodeJS
  - SonarQube Scanner
  - Nexus Artifact Uploader
- **SonarQube Server** (Running on a separate server or as a Docker container)
- **Nexus Repository Manager** (Configured to store artifacts)
- **Nginx** (For reverse proxy and deployment)
- **EC2 Instance / Vagrant VM** (To host the Node.js app)

## 📂 Folder Structure
```
📦 NodeJS-CI-CD
 ┣ 📂 src              # Application Source Code
 ┣ 📂 tests            # Unit & Integration Tests
 ┣ 📜 Jenkinsfile      # Jenkins Pipeline as Code
 ┣ 📜 sonar-project.properties  # SonarQube Config
 ┣ 📜 nginx.conf       # Nginx Configuration
 ┣ 📜 package.json     # Node.js Dependencies
 ┗ 📜 README.md        # Project Documentation
```
