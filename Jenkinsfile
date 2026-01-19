pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code checked out from GitHub'
            }
        }

        stage('List Files') {
            steps {
                sh 'ls -la'
            }
        }
    }
}
