pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'git clone https://github.com/mathis-pepin/Docker-CESI.git'
        sh 'git build https://github.com/mathis-pepin/Docker-CESI.git'
      }
    }

  }
}