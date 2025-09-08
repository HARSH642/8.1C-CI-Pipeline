pipeline {
    agent any
    stages {
        stage('Build') {
            steps { echo 'Building with Maven...' }
        }
        stage('Unit Tests') {
            steps { echo 'Running JUnit tests...' }
        }
        stage('Code Analysis') {
            steps { echo 'Analyzing code with SonarQube...' }
        }
        stage('Security Scan') {
            steps { echo 'Running security scan...' }
        }
        stage('Deploy to Staging') {
            steps { echo 'Deploying to staging server...' }
        }
        stage('Integration Tests on Staging') {
            steps { echo 'Running Selenium tests...' }
        }
        stage('Deploy to Production') {
            steps { echo 'Deploying to production...' }
        }
    }
}
