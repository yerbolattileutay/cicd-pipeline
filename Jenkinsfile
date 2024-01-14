pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(branch: 'main', url: 'https://github.com/yerbolattileutay/cicd-pipeline.git')
      }
    }

    stage('App build') {
      steps {
        sh 'chmod +x scripts/build.sh'
      }
    }

  }
}