pipeline {
  agent any
  stages {
    stage('Say Hello') {
      agent {
        node {
          label 'K2VM'
        }
        
      }
      steps {
        powershell(script: 'c:\\test.ps1', returnStatus: true, returnStdout: true)
      }
    }
  }
}