pipeline {
  agent {
    docker {
      image 'nginx'
      args '-d -p 9090:80 '
    }
    
  }
  stages {
    stage('build') {
      steps {
        echo 'go go'
        sh 'touch /tmp/aa'
      }
    }
  }
}