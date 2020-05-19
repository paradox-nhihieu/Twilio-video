pipeline {
    agent { docker { image 'node:latest' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                sh 'cd TwilioNodeServer/'
                sh 'npm start'
            }
        }
    }
}