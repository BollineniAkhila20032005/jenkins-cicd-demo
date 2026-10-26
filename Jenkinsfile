pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code fetched from GitHub'
            }
        }

        stage('Build') {
            steps {
                sh 'javac Hello.java'
                echo 'Build successful'
            }
        }

        stage('Test') {
            steps {
                sh 'java Hello'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment stage completed'
            }
        }
    }
}
