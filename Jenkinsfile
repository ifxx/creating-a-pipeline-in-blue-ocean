pipeline {
  agent {
    docker {
      image 'centos'
      args '-v /tmp/:/tmp/'
    }
    
  }
  stages {
    stage('build') {
      steps {
        echo 'go go'
        sh 'touch /tmp/aa'
        sh 'cp /etc/BUILDTIME .'
      }
    }
  }
}