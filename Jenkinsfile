pipeline {
  agent any
  stages {
    stage('Satage1') {
      steps {
        echo ' "${env.name}"'
        svn(url: 'http://git.virtusa.com/Insight6/dashboard.git', poll: true, changelog: true)
        startTomcat 'C:\\Projects\\blueocen\\apache-tomcat-8.0.3'
      }
    }
  }
  environment {
    name = 'Nalaka'
  }
}