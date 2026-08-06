pipeline {
    agent any

    stages {

        stage('Welcome') {
            steps {
                echo 'Welcome to Feature Branch'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building Feature Branch..."'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Running Feature Branch Tests..."'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deploying Feature Branch..."'
            }
        }
    }

    post {
        success {
            echo 'Feature Branch Build Completed Successfully!'
        }

        failure {
            echo 'Feature Branch Build Failed!'
        }
    }
}
