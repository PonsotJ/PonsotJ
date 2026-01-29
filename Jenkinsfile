pipeline {
  agent {
    node {
      label 'Messages_test'
    }

  }
  stages {
    stage('Message') {
      steps {
        echo 'Hello World'
      }
    }

  }
  environment {
    message = 'Hello world'
  }
}