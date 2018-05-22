pipeline {
  agent none
  stages {
    stage('Preparation') {
      steps {
        node(label: 'node') {
          echo '1'
        }

        ws(dir: '/tmp') {
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