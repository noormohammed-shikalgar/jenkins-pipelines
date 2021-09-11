pipeline{
    agent any
    tools{
        nodejs 'Node-16.9.1'
    }
    options{
        checkoutToSubdirectory('server')
    }
    stages{
        stage('NPM Install'){
            steps{
                sh 'pwd'
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