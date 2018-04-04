pipeline {
  agent any
  stages {
    stage('Satage1') {
      steps {
        echo ' "${env.name}"'
        svn(url: 'http://git.virtusa.com/Insight6/dashboard.git', poll: true, changelog: true)
       
      }
    }
  }
  environment {
    name = 'Nalaka'
  }
}
