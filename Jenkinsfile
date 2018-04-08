pipeline {
  agent any
  stages {
    stage('Satage1') {
      environment {
        a = 'A'
      }
      steps {
        echo 'withEnv($name)'
        echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
      }
    }
  }
  environment {
    name = 'Nalaka'
  }
}