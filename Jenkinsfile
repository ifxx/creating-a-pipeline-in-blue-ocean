pipeline {
  agent {
    docker {
      image 'centos'
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