pipeline {
  agent {
        docker { image 'node:16.13.1-alpine' }
    }
  stages {
    stage('version') {
      steps {
        sh 'docker ps'
      }
    }
    stage('hello') {
      steps {
        sh 'docker images'
      }
    }
  }
}
