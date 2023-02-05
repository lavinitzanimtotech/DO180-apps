/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'node:current-alpine3.16' } }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}

