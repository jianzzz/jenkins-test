pipeline {
  agent none
  stages {
    stage('Preparation') {
      steps {
        echo '1'
        catchError() {
          echo '12'
        }

      }
    }
    stage('Build') {
      steps {
        echo '1'
      }
    }
    stage('Results') {
      steps {
        echo '1'
      }
    }
  }
}