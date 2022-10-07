pipeline {
  agent any

    
    
  stages {


      stage('jdk 17') {
    tools {
        maven 'mvnapp'
        jdk 'JDK17'
  }
      steps {
          sh 'JAVA_HOME= ${tool "JDK17"}'
          sh 'echo $JAVA_HOME'
          sh 'java -version'
          sh 'javac -version'
          sh 'mvn clean package'
        }
      }
  }
}
