pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        echo 'Hello World'
        sh 'mvn test'
      }
    }
    stage('Install') {
      steps {
        sh 'mvn install'
      }
    }
  }
}