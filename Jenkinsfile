pipeline {
  agent none
  stages {
    stage('Preparation') {
      steps {
        echo 'Preparation'
        sh 'hello'
        timeout(time: 1, activity: true)
        retry(count: 1) {
          retry(count: 2)
        }

      }
    }
    stage('Build') {
      steps {
        echo 'build'
      }
    }
    stage('Results') {
      steps {
        echo 'Results'
      }
    }
  }
}