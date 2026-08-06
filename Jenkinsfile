pipeline {
    agent any

    stages {

        stage('Welcome') {
            steps {
                echo 'Welcome to Pipeline as Code'
            }
        }

        stage('Workspace') {
            steps {
                sh 'pwd'
            }
        }

        stage('List Files') {
            steps {
                sh 'ls -la'
            }
        }

        stage('Finish') {
            steps {
                echo 'Pipeline Executed Successfully!'
            }
        }
    }
}
