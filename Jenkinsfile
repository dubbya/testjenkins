pipeline {
  agent any
  stages {
    stage('Hi') {
      agent {
        node {
          label 'K2VM'
        }
        
      }
      steps {
        sleep 10
      }
    }
  }
}