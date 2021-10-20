pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Completed'
        timeout(time: 5, unit: 'SECONDS') {
          sh 'sleep 3'
        }
      }
    }
  stage('Test') {
      steps {
        echo 'Testing Complete'
      }
    }
      stage('Deploy') {
      steps {
        echo 'Deploy Completedd'
      }
    }
      stage('Notify') {
      steps {
        echo 'Notify Completed'
      }
    }
  }
}