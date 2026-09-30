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
                bat 'cd'
                bat 'dir /a'
                bat 'whoami'
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
