pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('Build image') {
      steps {
        sh 'docker build -t test-blueocean .'
      }
    }
  }
}