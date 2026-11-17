
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Login Application'
                bat 'if exist index.html (echo Build Successful) else (exit 1)'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Login Application'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Login Application Ready'
            }
        }
    }
}
