/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'node:16.17.1-alpine' } }
    stages {
        stage('test') {
            steps {
                sh 'npm i express'
            }
        }
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}
