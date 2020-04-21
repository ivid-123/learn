pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..............changed again new changes again'
                echo 'Waiting 5 minutes for deployment to complete prior starting smoke testing'
                sleep 300 // seconds
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
