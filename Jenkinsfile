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
        sh 'cat wibble'
      }
    }
    stage('sleep') {
      steps {
        sleep 3
      }
    }
  }
}