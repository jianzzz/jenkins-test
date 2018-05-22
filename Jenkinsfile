pipeline {
  agent {
    node {
      label 'test'
    }

  }
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
}