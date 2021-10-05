pipeline {
  agent {
    any {
      image 'node:6-alpine'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'Construir la app'
        sh 'cd /usr/bin/src'
        sh 'ls -las'
        sh '/usr/bin/npm install'
      }
    }

  }
}