pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        echo 'Hello World'
        bat 'C:\\TC\\Maven\\apache-maven-3.3.9\\bin\\mvn.cmd test'
      }
    }
    stage('Install') {
      steps {
        bat 'C:\\TC\\Maven\\apache-maven-3.3.9\\bin\\mvn.cmd install'
      }
    }
  }
}