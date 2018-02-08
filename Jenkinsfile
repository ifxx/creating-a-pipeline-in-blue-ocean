pipeline {
  agent {
    docker {
      image 'nginx'
      args '-p 9090:80'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh 'echo "hihi"'
      }
    }
  }
}