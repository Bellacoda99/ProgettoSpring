pipeline {
  agent any
  tools {
    maven 'mvnapp'
    jdk 'JDK17'
  }
    
    
  stages {


      stage('jdk 17') {
      steps {
        withEnv(["JAVA_HOME=${tool 'JDK17'}", "PATH=${tool 'JDK17'}/bin:${env.PATH}"]) {
          sh 'java -version'
          sh 'javac -version'
          sh 'mvn clean package'
        }
      }
  }
}