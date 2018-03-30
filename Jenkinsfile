pipeline {
  agent any
  stages {
    stage('Satage1') {
      steps {
        echo ' "${env.name}"'
        svn(url: 'http://10.61.10.25/svn/repo1/trunk/QA', poll: true, changelog: true)
      }
    }
    stage('s2') {
      steps {
        tempoTool(name: 'dd', body: 'ggg')
      }
    }
  }
  environment {
    name = 'Nalaka'
  }
}