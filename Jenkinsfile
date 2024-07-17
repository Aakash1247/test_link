pipeline {
    agent {
        docker { 
            image 'python:3.12.4-alpine3.20'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
