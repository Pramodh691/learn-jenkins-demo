pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Pulling code from GitHub'
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t jenkins-demo-app .'
            }
        }
    }
}
