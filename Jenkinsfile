pipeline {
    agent {
        docker { image 'node:16-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        },
         stage('Printing') {
            steps {
echo "hello World"
            }
        }
    }
}
