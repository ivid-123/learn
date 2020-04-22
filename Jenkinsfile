pipeline {
    agent {
         node { 
             label 'maven' 

         }
    } 

    stages {
        stage('Build') {
           
            steps {
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
