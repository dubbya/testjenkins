pipeline {
  agent any
  stages {
    stage('Say Hello') {
      agent any
      steps {
        powershell(script: 'c:\\test.ps1', returnStatus: true, returnStdout: true)
      }
    }
  }
}