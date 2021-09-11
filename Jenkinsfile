pipeline{
    agent any
    options{
        checkoutToSubdirectory('server')
    }
    stages{
        stage(name: 'NPM Install'){
            steps{
                sh 'npm install'
            }
        }
        stage(name: 'Build'){
            steps{
                sh 'ng build'
            }
        }
    }
}