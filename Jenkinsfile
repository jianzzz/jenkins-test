pipeline {
  agent none
  stages {
    stage('Build') {
      steps {
        load 'test.groovy'
      }
    }
    stage('Results') {
      steps {
        echo '1'
      }
    }
  }
  environment {
    e1 = '1'
  }
}