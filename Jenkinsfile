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
        echo 'go go'
        sh 'echo "hi hi hi">>/usr/share/nginx/html/index.html'
      }
    }
  }
}