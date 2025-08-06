# 🚀 DevOps Task 2 – Jenkins CI/CD Pipeline

[![Jenkins Build](https://img.shields.io/badge/Jenkins-Build-blue)](https://www.jenkins.io/)

This is a simple **Node.js application** integrated with a **Jenkins pipeline**.  
It demonstrates continuous integration and deployment using Jenkins.

---

## 📦 Tech Stack

- Node.js  
- Express.js  
- Jenkins  
- Git & GitHub

---

## 📁 Project Structure


---

## 📄 Jenkinsfile Overview

```groovy
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/tyagigaurav07/devops-jenkins-pipeline.git'
            }
        }
        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }
        stage('Run App') {
            steps {
                sh 'node app.js'
            }
        }
    }
}
