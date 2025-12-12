
pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                echo "Pulling latest code..."
            }
        }
        stage('Build') {
            steps {
                echo "Building docker compose..."
            }
        }
        stage('Deploy') {
            steps {
                echo "Running docker compose..."
                sh 'docker-compose up -d'
            }
        }
    }
}
