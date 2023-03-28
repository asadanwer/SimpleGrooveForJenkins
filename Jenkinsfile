pipeline {
    agent {
        docker { image 'node-16-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
        state('Prining') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
