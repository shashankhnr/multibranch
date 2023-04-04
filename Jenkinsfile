pipeline{
    agent any
    stages{
        stage("install"){
            steps{
               sh 'npm install' 
            }
        }
        stage('Test') {
            steps {
              sh 'echo "testing the application"'
            }  
        }
        stage('Deploy') {
            steps {
              sh 'echo "deployng application"'
            }
        }
    }
}
