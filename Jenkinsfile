pipeline {
  agent any
  stages {
    stage('Say Hello!') {
      steps {
        echo 'Hello How are you'
      }
    }
    stage('ListFiles') {
      steps {
        sh 'ls -lrt'
      }
    }
  }
}