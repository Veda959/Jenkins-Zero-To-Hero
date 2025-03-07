pipeline {
    agent any
    stages {
        stage('Clone Repo') {
            steps {
                git 'https://github.com/Veda959/Jenkins-Zero-To-Hero.git'
            }
        }
        stage('Build') {
            steps {
                echo "Building the application..."
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying the application..."
            }
        }
    }
}
