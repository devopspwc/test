// Work
pipeline {
   agent any
   triggers {
        cron('H/15 * * * *')
    }
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
