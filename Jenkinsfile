pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                sh 'cd compose && docker-compose up -d'
            }
        }
    }
}