pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        powershell(script: '/test.ps1', returnStatus: true, returnStdout: true)
      }
    }
  }
}