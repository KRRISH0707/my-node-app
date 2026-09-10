pipeline {
    agent any

    tools {
        nodejs 'node-20'
    }

    stages {

        stage('Checkout') {
            steps {
                echo 'Code checked out by Jenkins automatically'
            }
        }

        stage('Install Dependencies') {
            steps {
                bat 'npm install'
            }
        }

        stage('Run Tests') {
            steps {
                bat 'npm test'
            }
        }

        stage('Build') {
            steps {
                echo 'Build step would go here (e.g. npm run build)'
            }
        }
    }
}