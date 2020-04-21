pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        npm run install
        npm run build
        npm run lint
        npm run test
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
