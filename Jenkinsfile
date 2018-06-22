pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('say hello') {
      steps {
        echo "Hello World! ${MY_NAME}"
        sh 'java -version'
        echo "${g8uhcz_USR}"
        echo "${g8uhcz_PSW}"
      }
    }
  }
  environment {
    MY_NAME = 'Heng Zheng'
    TEST_USER = credentials('g8uhcz')
  }
  parameters {
    string(name: 'Name', defaultValue: 'whoever you are', description: 'Who should I say hi to?')
  }
}