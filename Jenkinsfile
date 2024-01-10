pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'hello'
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