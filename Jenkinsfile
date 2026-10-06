pipeline {
    agent any

    stages {
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
