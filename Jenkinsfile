pipeline {
  agent any
   stages {
    stage ('Build') {
      steps {
        sh '''#!/bin/bash
        echo  "This is the build"
        '''

     }
   }
  }
  stages {
    stage ('test') {
      steps {
        sh '''#!/bin/bash
        echo  "This is a test"
        '''
        
     }
   }
  }
  stages {
    stage ('deploy') {
      steps {
        sh '''#!/bin/bash
        echo  "This is a deployment"
        '''
        
     }
   }
  }
}