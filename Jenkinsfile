pipeline {
  agent any
  environment {
    TOKEN = credentials("token1")
  }
  stages {
    stage('Build') {
      steps {
        sh "curl -H 'Token: $TOKEN' https://some.api/"
      }
    }
  }
}
