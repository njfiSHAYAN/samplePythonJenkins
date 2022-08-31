pipeline {
  agent none
  stages {
    stage('version') {
      agent {
        docker {
          image 'docker:dind'
        }
      }
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
