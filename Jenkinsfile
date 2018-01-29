pipeline {
  agent any
  stages {
    stage('build') {
      agent any
      steps {
        sh 'mvn clean package'
      }
    }
  }
  environment {
    name = 'rohit'
  }
}