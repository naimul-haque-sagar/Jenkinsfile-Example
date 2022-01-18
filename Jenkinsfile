# Jenkinsfile-for-spring-boot

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
    
  }
}
