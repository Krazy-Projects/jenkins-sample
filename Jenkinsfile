/* Requires the Docker Pipeline plugin */
pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'curl http://localhost:9000/'
            }
        }
    }
}
