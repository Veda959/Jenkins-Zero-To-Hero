pipeline {
    agent { label 'jenkins-slave-linux-server' }
    stages {
        stage('Git Installation') {
        sh 'sudo yum install -y git'
        }
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
