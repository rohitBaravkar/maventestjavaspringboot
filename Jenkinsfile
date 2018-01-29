pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''echo "hello world"

maven clean package'''
      }
    }
  }
  environment {
    name = 'rohit'
  }
}