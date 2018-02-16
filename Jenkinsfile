pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'hello world'
        sh 'C:\\kituri\\Maven\\apache-maven-3.5.2\\bin\\mvn clean'
      }
    }
    stage('install') {
      steps {
        sh 'C:\\kituri\\Maven\\apache-maven-3.5.2\\bin\\mvn install'
      }
    }
  }
}