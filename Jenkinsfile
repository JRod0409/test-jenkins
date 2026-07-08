pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps{
                git branch: 'main', url: 'https://github.com/JRod0409/test-jenkins'
            }
        }
        stage('Build'){
              steps{
                  sh 'echo "building the app"'
              }
        }
        stage('Test'){
            steps{
                sh 'echo "Running test"'
            }
        }
        stage('Deploy'){
            steps{
                sh 'echo "Deploying app"'
            }
        }
    }
}
