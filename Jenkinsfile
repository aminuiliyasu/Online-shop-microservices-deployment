pipeline {
  agent any
  stages {
    stage('checkout Code') {
      parallel {
        stage('checkout Code') {
          steps {
            git(url: 'https://github.com/aminuiliyasu/Online-shop-microservices-deployment.git', branch: 'main')
          }
        }

        stage('') {
          steps {
            sh 'ls -la'
          }
        }

      }
    }

  }
}