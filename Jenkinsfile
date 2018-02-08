pipeline {
  agent {
    docker {
      image 'nginx'
      args '-it -p 9090:80'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        sh 'echo "hihi">>/usr/share/nginx/html/index.html'
      }
    }
  }
}