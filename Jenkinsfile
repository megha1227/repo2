
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh "ls -la"
                sh "sleep 4"
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}    
