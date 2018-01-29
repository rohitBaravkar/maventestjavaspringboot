pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''echo "hello world"

mvn clean package'''
      }
    }
  }
  environment {
    name = 'rohit'
  }
}