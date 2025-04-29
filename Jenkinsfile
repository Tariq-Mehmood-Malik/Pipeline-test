pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh '''pwd
date
sleep 30'''
      }
    }

    stage('print') {
      steps {
        echo 'hello'
      }
    }

  }
}