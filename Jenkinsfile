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
        sh 'pwd > /tmp/pwd'
        sh 'cp /etc/BUILDTIME /tmp'
        sh 'hostname > /tmp/hostname'
      }
    }
  }
}