pipeline {
  agent {
    docker {
      image 'python:3.5.1'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }

  }
}