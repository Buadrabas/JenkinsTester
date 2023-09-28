pipeline {
    agent docker { 'ubuntu:latest' }
    stages {
        stage('Startup Build Step') {
            steps {
                sh 'gcc --version'
            }
        }
    }
}