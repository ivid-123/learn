pipeline {
    agent any

    stages {
        stage('Build') {
           
            steps {
                echo 'tstigngg'
                sh 'node --version'
                sh 'npm --version'
                echo 'ng verion'
                sh 'npm install @angular/cli@7.3.9'
                echo 'Install completed'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
