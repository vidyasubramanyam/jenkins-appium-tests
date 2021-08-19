pipeline {
    agent any
    tools {nodejs "node"}
    stages {
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
