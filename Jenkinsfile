pipeline{
    agent any
    tools{
        nodejs 'Node-16.9.1'
    }
    stages{
        stage('NPM Install'){
            steps {
                sh "pwd"
                dir('your-sub-directory') {
                sh "pwd"
                }
                sh "pwd"
            }
        }
        stage('Build'){
            steps{
                sh 'cd server && npm install && ng build'
            }
        }
    }
}