pipeline {
  agent none
  stages {
    stage('Preparation') {
      steps {
        archiveArtifacts(allowEmptyArchive: true, caseSensitive: true, defaultExcludes: true, fingerprint: true, onlyIfSuccessful: true, artifacts: 'artifact', excludes: 'excludes')
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