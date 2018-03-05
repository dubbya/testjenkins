pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        powershell(script: 'Write-Output "Hello, World!"', returnStatus: true, returnStdout: true)
      }
    }
  }
}