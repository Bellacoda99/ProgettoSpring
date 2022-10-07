pipeline {
  agent any
  tools {
    maven 'mvnapp'
    jdk 'JDK17'
  }
    
    
  stages {


      stage('jdk 17') {
      steps {

          sh 'java -version'
          sh 'javac -version'
          sh 'mvn clean package'
        }
      }
  }
}
