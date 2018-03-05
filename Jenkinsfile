pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        powershell(script: 'c:\\test.ps1', returnStatus: true, returnStdout: true)
      }
    }
  }
}