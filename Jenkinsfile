pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Code checked out successfully.'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building Application..."'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Running Tests..."'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deployment Completed."'
            }
        }
    }
}
