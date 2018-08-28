pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello World'
      }
    }
    stage('Deploy') {
      steps {
        input 'Should we continue'
      }
    }
  }
}