pipeline {
    agent any

    stages {
        stage('Start test') {
            steps {
                echo 'Testing..'
                sh '''
                    appium --version
                    node --version
                    node index.js
                '''
            }
        }
    }
}
