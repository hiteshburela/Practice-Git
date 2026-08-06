pipeline {
    agent any

    stages {

        stage('Welcome') {
            steps {
                echo 'Welcome to Pipeline from SCM'
            }
        }

        stage('Print Workspace') {
            steps {
                sh 'pwd'
            }
        }

        stage('List Files') {
            steps {
                sh 'ls -la'
            }
        }

        stage('Create File') {
            steps {
                sh 'echo "Hello from Jenkins Pipeline" > output.txt'
                sh 'cat output.txt'
            }
        }

        stage('Print Date') {
            steps {
                sh 'date'
            }
        }

        stage('Finish') {
            steps {
                echo 'Pipeline from SCM Executed Successfully!'
            }
        }
    }

    post {
        success {
            echo 'Build Completed Successfully!'
        }

        failure {
            echo 'Build Failed!'
        }
    }
}
