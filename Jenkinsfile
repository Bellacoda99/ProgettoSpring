pipeline {
  agent any
  tools {
    maven 'mvnapp'
    jdk 'JDK17'
  }
    
    
  stages {


      stage('jdk 17') {
      steps {
        env.JAVA_HOME="${tool 'JDK17'}"
        env.PATH="${env.JAVA_HOME}/bin:${env.PATH}"

          sh 'java -version'
          sh 'javac -version'
          sh 'mvn clean package'
        }
      }
  }
}
