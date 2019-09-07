pipeline {
    agent any
    stages {
        stage('Install packages') {
            steps {
                sh 'npm install'
            }
        }
        stage('Execute tests') {
            steps {
                sh 'npm run build'
            }
        }
        stage('Build application') {
            steps {
                sh 'npm run build'
            }
        }
    }
}