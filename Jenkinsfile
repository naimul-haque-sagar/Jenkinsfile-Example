pipeline {
  agent {
    label 'label name'
  }
  
  triggers {
    pollSCM '* * * * *'
  }
  
  environment {
    MAINTAINER = 'naimulhaquesagar@gmail.com'
    APP_NAME = 'spring-boot-app'
    PERMISSION_FOR_PUBLIC_USE = 'true'
  }
  
  stages {
    stage('one') {
      steps {
        echo 'This is step one'
      }
      
      steps {
        echo 'This is step two'
      }
    }
    
    parallel {
      stage('parallel stage') {
        echo 'This is parallel stage one'
      }
      
      stage('parallel stage') {
        echo 'This is parallel stage two'
      }
    }
    
    stage('two) {
      parallel {
        steps {
          echo 'parallel steps'
        }
        
        steps {
          echo 'parallel steps'
        }
      }
    }
          
          
  }
}
