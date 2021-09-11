pipeline{
    agent any
    tools{
        nodejs 'Node-16.9.1'
    }
    stages{
        stage('NPM Install'){
            steps{
                sh 'cd server'
                sh 'npm install'
            }
        }
        stage('Build'){
            steps{
                sh 'cd server'
                sh 'ng build'
            }
        }
    }
}