pipeline {
    agent { docker { image 'node:8' } }
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