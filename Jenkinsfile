pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                echo 'building'
                sh 'node --version'
            }
        }
    }
}
