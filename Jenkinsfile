pipeline {
    agent any
    stages {
        stage('Checkout code') {
            steps {
                git 'https://github.com/dawrinmiller/git_learning'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the app'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the app'
            }
        }
    }
}
