pipeline {
    agent any
    tools {nodejs "node"}
    stages {
        stage('Install software') {
            steps {
                echo 'installing..'
                sh '''
                   npm install webdriverio
                   echo "${env.WORKSPACE}"
                '''
            }
        }
        stage('Start test') {
            steps {
                echo 'Testing..'
                sh '''
                    node --version
                    node index.js
                '''
            }
        }
    }
}
