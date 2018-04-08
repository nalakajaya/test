pipeline {
  agent any
  stages {
    stage('Satage1') {
      steps {
        echo ' $env.name'
        bat123 'nn'
        echo '"${env.WORKSPACE}"'
      }
    }
  }
  environment {
    name = 'Nalaka'
  }
}