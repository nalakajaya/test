pipeline {
  agent any
  stages {
    stage('Satage1') {
      environment {
        a = 'A'
      }
      steps {
        echo '" ${env.name}"'
        echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
      }
    }
  }
  environment {
    name = 'Nalaka'
  }
}