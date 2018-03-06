pipeline {
  agent {
    node {
      label 'master'
    }
    
  }
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
    stage('') {
      agent {
        node {
          label 'master'
        }
        
      }
      steps {
        sleep 10
      }
    }
  }
}