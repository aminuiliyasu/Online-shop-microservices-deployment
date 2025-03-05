pipeline {
  agent any
  stages {
    stage('checkout Code') {
      steps {
        git(url: 'https://github.com/aminuiliyasu/Online-shop-microservices-deployment.git', branch: 'main')
      }
    }

    stage('log') {
      steps {
        sh 'ls -la'
      }
    }

  }
}