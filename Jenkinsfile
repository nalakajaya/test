pipeline {
  agent any
  stages {
    stage('Satage1') {
      steps {
        echo ' "${name}"'
        svn(url: 'http://git.virtusa.com/Insight6/dashboard.git', poll: true, changelog: true)
        bat123 'C:\\Users\\nkulasekara\\Downloads\\insight-analyzer-win-64 (3)\\insight-analyzer-win\\tools\\findbugs\\bin'
        bat123 'nn'
      }
    }
  }
  environment {
    name = 'Nalaka'
  }
}