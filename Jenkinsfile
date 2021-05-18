pipeline {
  agent {
    docker {
      // image 'ttnrhjendev1:5000/njc/docker:dind-rootless'
      image 'ttnrhjendev1:5000/njc/podman:3'
      args '--privileged --add-host ttnrhjendev1:192.168.20.103'
      reuseNode true
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
