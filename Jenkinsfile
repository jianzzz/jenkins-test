pipeline {
  agent none
  stages {
    stage('Preparation') {
      steps {
        echo 'Preparation'
        sh 'hello'
        timeout(time: 1, activity: true)
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