pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build'
        echo 'Build1'
        echo 'Build2'
      }
    }
    stage('Init') {
      parallel {
        stage('P1') {
          steps {
            echo 'launch p1 in background'
          }
        }
        stage('setup') {
          steps {
            echo 'setup'
          }
        }
      }
    }
    stage('P1') {
      steps {
        echo 'ffff'
      }
    }
    stage('ParallelSteps') {
      parallel {
        stage('a1') {
          steps {
            echo 'ps1'
          }
        }
        stage('a2') {
          steps {
            echo 'ps2'
          }
        }
        stage('a3') {
          steps {
            echo 'ps3'
          }
        }
      }
    }
    stage('Cleanup') {
      steps {
        echo 'cleanup'
      }
    }
    stage('Check P1 status') {
      steps {
        echo 'Check'
      }
    }
    stage('S2') {
      steps {
        echo 'S2'
      }
    }
  }
}