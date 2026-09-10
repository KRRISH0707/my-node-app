pipeline {
    agent any
    tools {
        nodejs 'node-lts'
    }
    stages {
        stage('Checkout') {
            steps {
                echo 'Code checked out by Jenkins automatically'
            }
        }
        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }
        stage('Run Tests') {
            steps {
                sh 'npm test'
            }
        }
        stage('Build') {
            steps {
                echo 'Build step would go here (e.g. npm run build)'
            }
        }
    }
}