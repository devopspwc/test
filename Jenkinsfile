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
                ls -l
                pwd
                '''
                }
             }
          }
      }
  }
