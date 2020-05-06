// Work
pipeline {
   agent any
   stages {
     stage('TEST') {
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
   }
