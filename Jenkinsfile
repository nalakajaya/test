pipeline {
  agent none
  stages {
    stage('Satage1') {
      steps {
        build(job: 'test', quietPeriod: 1)
        sh 'echo "stage1"'
      }
    }
  }
  environment {
    test1 = '1'
  }
}