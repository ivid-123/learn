pipeline {
  agent node
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        npm install
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
