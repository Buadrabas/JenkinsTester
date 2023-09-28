pipeline {
    agent { docker { image 'ubuntu:latest' } }
    stages {
        stage('build') {
            steps {
                sh 'gcc --version'
                sh 'gcc -c src/main.c'
                sh "gcc"
                sh "./main"
            }
        }
    }
}