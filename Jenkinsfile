pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        bat 'echo "this is build ${BUILD_NUMBER} and ${DEMO1}"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}