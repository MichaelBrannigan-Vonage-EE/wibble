pipeline {
  agent any
  stages {
    stage('Wibble') {
      steps {
        echo 'Wibble'
        sh 'echo wibble > wibble'
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