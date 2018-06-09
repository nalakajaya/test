pipeline {
  agent {
    docker {
      image 'fdfd'
      args 'fgff'
    }

  }
  stages {
    stage('Satage1') {
      parallel {
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
        stage('satage1 prallel') {
          steps {
            echo 'eeee'
            bat 'vvv'
          }
        }
        stage('S1') {
          steps {
            echo 'ccc'
          }
        }
      }
    }
    stage('s2') {
      steps {
        echo 'eee'
      }
    }
    stage('s3') {
      agent {
        dockerfile {
          filename 'eeee'
        }

      }
      environment {
        ee = 'rr'
      }
      steps {
        echo 'cccxcx'
      }
    }
    stage('s4') {
      parallel {
        stage('s4') {
          agent {
            docker {
              image 'sdsds'
              args 'sdsdsd'
            }

          }
          environment {
            ttt = 'qeq'
          }
          steps {
            echo 'fff'
          }
        }
        stage('s4 1') {
          steps {
            echo 'ww'
            sh 'set adc'
          }
        }
        stage('rr') {
          steps {
            sleep 34
          }
        }
        stage('error') {
          steps {
            sleep(time: 444, unit: 'MINUTES')
          }
        }
      }
    }
    stage('e1') {
      steps {
        echo 'ss'
      }
    }
    stage('ff') {
      steps {
        node(label: 'fff')
      }
    }
  }
  environment {
    name = 'Nalaka'
    dsd = 'fff'
  }
}