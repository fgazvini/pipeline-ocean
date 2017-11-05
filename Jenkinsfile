pipeline {
  agent {
    docker {
      image 'node:7-alpine'
    }
    
  }
  stages {
    stage('test') {
      agent {
        docker {
          image 'node:7-alpine'
        }
        
      }
      steps {
        sh 'node --version'
      }
    }
  }
}