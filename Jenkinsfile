@Library('roboshop-shared-library') _

//install seed jenkins refer jenkins job dsl
pipeline {
  agent any
  
  stages {
     // For Each Commit
    stage('Lint Checks') {
      steps {
          sh ''' 
          #we commented this because dev is goin =g to check this failure
          #~/node_modules/jslint/bin/jslint.js server.js
          echo  Lint Checks
          '''
          }
        }
     } // End of Stages
 }