pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                git branch: 'jenkins-test', url: 'https://github.com/codeboylal/hbl2-django-todo-docker-project.git'
            }
        }
        
        stage('Build & Deploy') {
            steps {
                sh 'docker compose down || true'
                sh 'docker compose up -d --build'
            }
        }
    }
}