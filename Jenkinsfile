pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'docker build -t Mon_node -f https://github.com/mathis-pepin/Docker-CESI .'
      }
    }

  }
}