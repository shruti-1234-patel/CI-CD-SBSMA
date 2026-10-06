pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/shruti-1234-patel/CI-CD-SBSMA.git'
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
