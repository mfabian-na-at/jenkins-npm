pipeline {
  agent {
    docker {
      image 'mhart/alpine-node:slim-12'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'Construir la app'
        sh 'cd /usr/bin'
        sh 'ls -las'
        sh 'node --version'
      }
    }

  }
}