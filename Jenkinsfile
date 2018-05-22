pipeline {
  agent none
  stages {
    stage('Preparation') {
      steps {
        timeout(time: 1, unit: 'MINUTES')
        timeout(unit: 'HOURS', time: 1)
        timeout(unit: 'DAYS', time: 1)
        timeout(time: 1, unit: 'NANOSECONDS')
        timeout(time: 1, unit: 'MICROSECONDS')
        timeout(time: 1, unit: 'MILLISECONDS')
        bat(script: '/tmp/run.bat', encoding: 'utf8', returnStatus: true, returnStdout: true)
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