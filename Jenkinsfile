pipeline {
  agent none
  stages {
    stage('Preparation') {
      steps {
        echo 'Preparation'
        git 'https://github.com/jianzzz/jenkins-test.git'
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
        sleep(unit: 'SECONDS', time: 1)
      }
    }
  }
}