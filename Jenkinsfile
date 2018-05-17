pipeline {
  agent none
  stages {
    stage('Preparation') {
      steps {
        echo 'Preparation'
        sh 'hello'
        timeout(time: 1, activity: true)
        retry(count: 1)
        sleep 1
        bat(returnStatus: true, returnStdout: true, encoding: 'utf8', script: '/test/')
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