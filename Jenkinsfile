pipeline {
    agent {
         node { 
             label 'nodejs' 
         }
    } 

    stages {
        stage('Build') {
           
            steps {
                echo 'Building..............changed again new changes again'
                echo 'Waiting 5 minutes for deployment to complete prior starting smoke testing'
                echo 'New pull request changes'
                sleep 10 // seconds
                sh 'node --version'
                sh 'npm --version'
               
                
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
