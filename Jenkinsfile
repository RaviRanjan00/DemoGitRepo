pipeline {
  agent any
  stages {
    stage('nnew') {
      steps {
        echo 'Hi I\'m ready to test'
        sh 'mvn clean test'
        build 'New'
      }
    }

  }
}