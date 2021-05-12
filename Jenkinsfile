pipeline {
  agent {
    docker {
      image 'ttnrhjendev1:5000/njc/docker:dind-rootless'
    }

  }
  stages {
    stage('Info') {
      steps {
        sh '''sh \'docker version\'
sh \'docker info\''''
      }
    }

  }
}