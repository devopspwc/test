// Work
pipeline {
   agent any
   stages {
     stage('UAT') {
      steps {
            dir ('') {
                sh label: '', script: '''
                #!/bin/bash
                TEST='this is a test'
                echo $TEST
                gatsby -v
                '''
                }
             }
          }
      }
   post { 
        always { 
            echo 'I will always say Hello again!'
        }
      }
    }
  }
