pipeline {
  agent {
    docker {
      image '12'
      args '12'
    }

  }
  stages {
    stage('Preparation') {
      steps {
        sh '''echo 1;
ls /tmp;'''
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