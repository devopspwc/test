// Work
pipeline {
   agent any
   triggers { pollSCM('H/15 * * * *')
       }
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
