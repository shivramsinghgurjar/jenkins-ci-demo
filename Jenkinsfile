pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/shivramsinghgurjar/jenkins-ci-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'No build required for Python project'
            }
        }

        stage('Test') {
            steps {
                bat 'pip install pytest'
                bat 'pytest'
            }
        }
    }
}