pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo "Building the project"'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Running tests"'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deploying the project"'
            }
        }
    }

    post {
        success {
            echo 'Pipeline succeeded!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
