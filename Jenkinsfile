pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        sh '''apt update
apt install -y git'''
        git(url: 'https://github.com/Dave-dev-kt/curriculum-app.git', branch: 'dev')
      }
    }

  }
}