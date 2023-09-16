pipeline{
    agent{
        docker {
            image
        }
    }

    stages{
        stage('build'){
            steps{
                sh 'clang --version'
                sh 'clang -c src/main.c -o build/main.o'
                sh 'clang'
            }
        }
    }
}