pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Hello DevOps World!') {
      steps {
        echo 'Hello DevOps'
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Rosie'
  }
}