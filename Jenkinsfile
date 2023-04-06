pipeline {
    agent any
    stages {
         stage('install node') {
            steps { 
                bat 'echo "npm install"'
            }
        }
        stage('Test') {
            steps { 
                bat 'echo "testing the application"'
            }
        }
         stage('Deploy') {
            steps { 
                bat 'echo "deploying the application"'
            }
        }
    }
}
