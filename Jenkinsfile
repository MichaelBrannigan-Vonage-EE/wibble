pipeline {
  agent any
  stages {
    stage('Wibble') {
      steps {
        echo 'Wibble'
      }
    }
    stage('ls') {
      steps {
        sh 'ls'
      }
    }
    stage('sleep') {
      steps {
        sleep 3
      }
    }
  }
}