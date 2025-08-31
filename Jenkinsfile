pipeline {
    agent any
    stages {
        stage('Build') {
            steps { echo 'Building with Maven' }
        }
        stage('Unit and Integration Tests') {
            steps { echo 'Running JUnit and Cucumber tests' }
        }
        stage('Code Analysis') {
            steps { echo 'Analyzing code with SonarQube' }
        }
        stage('Security Scan') {
            steps { echo 'Scanning with OWASP Dependency-Check' }
        }
        stage('Deploy to Staging') {
            steps { echo 'Deploying to AWS EC2 staging server' }
        }
        stage('Integration Tests on Staging') {
            steps { echo 'Running Postman tests on staging' }
        }
        stage('Deploy to Production') {
            steps { echo 'Deploying to AWS EC2 production server' }
        }
    }
}
