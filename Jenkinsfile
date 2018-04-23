pipeline {
  agent any
  stages {
    stage('Satage1') {
      environment {
        a = 'A'
      }
      steps {
        echo 'withEnv($env.name)'
        echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
        echo 'heloo'
      }
    }
  }
  environment {
    name = 'Nalaka'
  }
}