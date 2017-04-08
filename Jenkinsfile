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
        parallel(
          "ListFiles": {
            sh 'ls -lrt'
            
          },
          "": {
            tool(name: 'java', type: 'java')
            
          }
        )
      }
    }
  }
  environment {
    xy = 'sav'
  }
}