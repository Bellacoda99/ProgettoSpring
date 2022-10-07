pipeline {
  agent any
  tools {
    maven 'mvnapp'
    java 'JDK17'
  }
    
    
  stages {
    stage('Java') {
      steps {
        sh 'mvn package'
      }
    }
  }
}