# 🚀 DevOps Task 2 – Jenkins CI/CD Pipeline

[![Jenkins Build](https://img.shields.io/badge/Jenkins-Build-blue)](https://www.jenkins.io/)

This is a simple **Node.js application** integrated with a **Jenkins pipeline**.  
The purpose is to demonstrate continuous integration and deployment using Jenkins.

---

## 📦 Tech Stack

- **Node.js**
- **Express.js**
- **Jenkins (CI/CD)**
- **Git & GitHub**

---

## 📁 Project Structure

devops-jenkins-pipeline/
├── node_modules/
├── app.js
├── package.json
├── package-lock.json
└── Jenkinsfile

---

## 📄 Jenkinsfile Overview

This file defines the stages Jenkins will run:

- ✅ **Checkout**: Clones the repository
- 🧰 **Install Dependencies**: Runs `npm install`
- 🧪 **Build/Test**: Starts the app
- 🚀 **Deploy**: (Optional, if added)

---

## 🛠️ Setup Instructions

1. **Clone the repository**  
   ```bash
   git clone https://github.com/tyagigaurav07/devops-jenkins-pipeline.git
   cd devops-jenkins-pipeline
   npm install
   npm install
