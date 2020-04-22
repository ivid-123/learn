pipeline {
    agent {
         node { 
             label 'nodejs' 

         }
    } 

    stages {
        stage('Build') {
           
            steps {
                // sh 'node --version'
                // sh 'npm --version'
                // echo 'ng verion'
                // sh 'npm install @angular/cli@7.3.9'
                echo 'Install completed hellow world'
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
