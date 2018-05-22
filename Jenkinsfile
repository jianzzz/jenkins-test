pipeline {
  agent none
  stages {
    stage('Preparation') {
      steps {
        sh '''echo 1;
ls /tmp;'''
        echo '1212'
        timeout(time: 1, activity: true) {
          sh '12'
          echo '12'
        }

        retry(count: 2) {
          echo '1'
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