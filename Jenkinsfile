pipeline {
  agent {
    docker {
      image 'nginx'
      args '-p 80:9090'
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