pipeline {
  agent none
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            script {
              echo "1"
            }

          }
        }
        stage('Build1') {
          steps {
            echo '12'
          }
        }
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