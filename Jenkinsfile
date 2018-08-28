pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello World'
      }
    }
    stage('error') {
      agent any
      steps {
        sh 'java --version'
      }
    }
  }
}