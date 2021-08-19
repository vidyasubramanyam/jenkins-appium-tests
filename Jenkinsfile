pipeline {
    agent any

    stages {
        stage('Start test') {
            steps {
                echo 'Testing..'
                sh '''
                    node index.js
                '''
            }
        }
    }
}