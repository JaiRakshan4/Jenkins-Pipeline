pipeline {
    agent any
    stages {
        stage('Build') {
            steps { echo 'Building code using Maven...' }
        }
        stage('Unit and Integration Tests') {
            steps { echo 'Running unit and integration tests...' }
        }
        stage('Code Analysis') {
            steps { echo 'Analyzing code with SonarQube...' }
        }
        stage('Security Scan') {
            steps { echo 'Performing security scan with Snyk...' }
        }
        stage('Deploy to Staging') {
            steps { echo 'Deploying to AWS EC2 staging instance...' }
        }
        stage('Integration Tests on Staging') {
            steps { echo 'Running integration tests on staging...' }
        }
        stage('Deploy to Production') {
            steps { echo 'Deploying to production server...' }
        }
    }
}
// trigger automatic build test
