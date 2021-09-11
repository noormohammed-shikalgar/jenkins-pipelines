pipeline{
    agent any
    tools{
        nodejs 'Node-16.9.1'
    }
    stages{
        stage('NPM Install'){
            steps {
                sh "pwd"
                dir('server') {
                    sh "npm install"
                }
            }
        }
        stage('Build'){
            steps{
                sh 'cd server && npm install && ng build'
            }
        }
    }
}