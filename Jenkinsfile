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
                sh 'npm start &'
            }
        }
    }
}
