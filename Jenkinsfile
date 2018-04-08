pipeline {
  agent any
  stages {
    stage('Satage1') {
      steps {
        echo ' $env.name'
        echo '"${env.WORKSPACE}"'
      }
    }
  }
  environment {
    name = 'Nalaka'
  }
}