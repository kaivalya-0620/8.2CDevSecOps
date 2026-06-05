pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Stage 1: Build - Using Maven to compile and package the code.'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Stage 2: Unit and Integration Tests - Using JUnit for unit tests and Selenium for integration tests.'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Stage 3: Code Analysis - Using SonarQube to analyse code against industry standards.'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Stage 4: Security Scan - Using OWASP Dependency Check to identify vulnerabilities.'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Stage 5: Deploy to Staging - Deploying application to AWS EC2 staging instance.'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Stage 6: Integration Tests on Staging - Running integration tests using Selenium.'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Stage 7: Deploy to Production - Deploying application to AWS EC2 production instance.'
            }
        }
    }
}
