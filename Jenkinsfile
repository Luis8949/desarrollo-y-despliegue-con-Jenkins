pipeline {
  agent {
    docker {
      image 'node:12'
      args 'Modulo3'
    }

  }
  stages {
    stage('Modulo3') {
      steps {
        sh 'npm /install'
      }
    }

  }
  environment {
    built = ''
  }
}