pipeline {
    agent { label 'jenkins-slave-linux-server' }

    stages {
        stage('Install Git') {
            steps {
                sh 'sudo yum install -y git'
            }
        }

        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/Veda959/Jenkins-Zero-To-Hero.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building the application..."
            }
        }
    }
}

