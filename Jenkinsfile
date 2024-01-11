pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''npm install
'''
      }
    }

    stage('Test') {
      environment {
        CI = 'true'
      }
      steps {
        echo 'hello'
      }
    }

  }
}