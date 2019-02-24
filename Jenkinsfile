pipeline {
  agent { docker 'node:6.3' }
  stages {
    stage('show npm version') {
      steps {
        sh 'npm --version' 
      }
    }
  }
}
