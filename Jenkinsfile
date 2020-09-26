pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-p 13000:3000'
    }

  }
  stages {
    stage('') {
      steps {
        sh 'sh \'npm install\''
      }
    }

  }
}