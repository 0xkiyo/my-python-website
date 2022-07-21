# Jenkinsfile (Declarative Pipeline)
# This is a testing
pipeline {
    agent { docker { image 'python:3.10.1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python3 --version'
                sh 'echo "Hello World"'
            }
        }
    }
}
