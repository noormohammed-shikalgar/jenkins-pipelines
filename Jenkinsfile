pipeline{
    agent any
    options{
        checkoutToSubdirectory('server')
    }
    stages{
        stage('NPM Install'){
            steps{
                sh 'npm install'
            }
        }
        stage('Build'){
            steps{
                sh 'ng build'
            }
        }
    }
}