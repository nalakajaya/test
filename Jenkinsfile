pipeline {
  agent any
  stages {
    stage('Satage1') {
      agent any
      environment {
        a = 'A'
      }
      steps {
        echo ' $name'
        echo '$a'
      }
    }
  }
  environment {
    name = 'Nalaka'
  }
}