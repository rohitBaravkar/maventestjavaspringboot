pipeline {
  agent any
  stages {
    stage('build') {
      agent any
      steps {
        sh 'echo mvn -version'
      }
    }
  }
  environment {
    name = 'rohit'
  }
}