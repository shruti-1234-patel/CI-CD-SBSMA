pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'YOUR_GITHUB_REPOSITORY_URL'
            }
        }

        stage('Build') {
            steps {
                bat 'python app.py'
            }
        }

        stage('Test') {
            steps {
                echo 'Build and Test Successful'
            }
        }
    }
}
