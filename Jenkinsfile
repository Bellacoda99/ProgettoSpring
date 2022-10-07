pipeline {
  agent any

    
    
  stages {


      stage('jdk 17') {
    tools {
        maven 'mvnapp'
        jdk 'JDK17'
  }
      steps {

          sh 'java -version'
          sh 'javac -version'
          sh 'mvn clean package'
        }
      }
  }
}
