pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello world!"'
                sh 'docker --version'
                sh 'docker-compose --version'
            }
        }
    }
}
