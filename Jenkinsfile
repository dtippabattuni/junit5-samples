pipeline {
  agent any
  stages {
    stage('Say Hello!') {
      steps {
        parallel(
          "Say Hello!": {
            echo 'Hello How are you'
            
          },
          "SayHolla": {
            echo 'Holla'
            
          },
          "PrintBonJor": {
            echo 'Bon Jour'
            
          }
        )
      }
    }
    stage('ListFiles') {
      steps {
        sh 'ls -lrt'
      }
    }
  }
}