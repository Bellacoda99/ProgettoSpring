pipeline {
  agent any
  tools {
    maven 'mvnapp'
    jdk 'JDK17'
  }
    
    
  stages {
    stage('Java') {
      steps {
        sh 'mvn package'
      }
    }
  }
}