pipeline {
  agent {
    node {
      label 'test'
    }

  }
  stages {
    stage('Build') {
      steps {
        build(job: 'job', propagate: true, quietPeriod: 2, wait: true)
      }
    }
    stage('Results') {
      steps {
        echo '1'
      }
    }
  }
}