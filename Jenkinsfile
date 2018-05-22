pipeline {
  agent {
    node {
      label 'test'
    }

  }
  stages {
    stage('Preparation') {
      steps {
        node(label: 'test') {
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