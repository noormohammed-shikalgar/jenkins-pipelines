pipeline{
    agent any
    tools{
        nodejs 'Node-16.9.1'
    }
    stages{
        stage('NPM Install'){
            steps{
                dir('server'){
                    sh 'pwd'
                    sh 'npm install'
                }
            }
        }
        stage('Build'){
            dir('server'){
                steps{
                    sh 'ng build'
                }
            }
        }
    }
}