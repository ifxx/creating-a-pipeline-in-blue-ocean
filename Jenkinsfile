pipeline {
  agent {
    docker {
      image 'nginx'
      args '-p 9090:80'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        sh 'echo "hihi"'
      }
    }
  }
}