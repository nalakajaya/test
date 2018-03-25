pipeline {
  agent any
  stages {
    stage('Satage1') {
      steps {
        echo ' ${env.name}'
      }
    }
    stage('stage3') {
      steps {
        echo ' ${name}'
      }
    }
  }
  environment {
    name = 'Nalaka'
  }
}