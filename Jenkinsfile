pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('say hello') {
      steps {
        echo "Hello World! ${MY_NAME}"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Heng Zheng'
  }
}