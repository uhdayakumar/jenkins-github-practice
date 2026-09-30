pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/uhdayakumar/jenkins-github-practice.git'
            }
        }

        stage('Verify Workspace') {
            steps {
                sh 'pwd'
                sh 'ls -la'
                sh 'whoami'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage completed'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage completed'
            }
        }
    }
}
