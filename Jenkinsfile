pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Hello DevOps World!') {
      steps {
        echo 'Hello DevOps'
        echo "${TEST_USER_USR}"
        echo "${TEST_USER_PSW}"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Rosie'
    TEST_USER = credentials('test-user')
  }
}