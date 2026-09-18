pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Build the code using Maven to compile the source and package the application into a deployable artefact.'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Run unit tests with JUnit and integration tests with Selenium to verify components work together as expected.'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Analyse the code using SonarQube to ensure it meets industry coding standards.'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Scan the code for known vulnerabilities using OWASP Dependency-Check.'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Deploy the application to a staging server hosted on an AWS EC2 instance.'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Run integration tests on the staging environment to confirm the application behaves as expected in a production-like setup.'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Deploy the application to the production server hosted on an AWS EC2 instance.'
            }
        }
    }
}
