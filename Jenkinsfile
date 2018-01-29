pipeline {
  agent any
  stages {
    stage('build') {
      agent any
      steps {
        sh 'mvn clean build'
      }
    }
  }
  environment {
    name = 'rohit'
  }
}