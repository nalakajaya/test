pipeline {
  agent none
  stages {
    stage('Satage1') {
      steps {
        echo '1'
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