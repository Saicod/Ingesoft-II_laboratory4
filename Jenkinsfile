pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Checks'
      }
    }

    stage('Testing') {
      parallel {
        stage('Testing') {
          steps {
            echo 'Testing Phase'
          }
        }

        stage('Unit Test') {
          steps {
            echo 'Unit Testing'
          }
        }

        stage('Widget Test') {
          steps {
            echo 'Widget Testing'
          }
        }

        stage('Integration test') {
          steps {
            echo 'Integration Testing'
          }
        }

      }
    }

    stage('OS Test') {
      parallel {
        stage('OS Test') {
          steps {
            echo 'Begin OS Test'
          }
        }

        stage('Android') {
          steps {
            echo 'Android Testing'
          }
        }

        stage('iOS') {
          steps {
            echo 'iOS Testing'
          }
        }

      }
    }

    stage('Security') {
      parallel {
        stage('Security') {
          steps {
            echo 'Start Segurity Stage'
          }
        }

        stage('Internal Pentest') {
          steps {
            echo 'Start Internat Pentest'
          }
        }

        stage('External Pentest') {
          steps {
            echo 'Start External Pentest'
          }
        }

      }
    }

    stage('Staging') {
      parallel {
        stage('Staging') {
          steps {
            echo 'Start Staging'
          }
        }

        stage('Smoke Test') {
          steps {
            echo 'Smoke Testing'
          }
        }

        stage('Chaos Engineering') {
          steps {
            echo 'Chaos Engineering'
          }
        }

      }
    }

    stage('Deployment') {
      parallel {
        stage('Deployment') {
          steps {
            echo 'Deployment Stage'
          }
        }

        stage('App Store') {
          steps {
            echo 'App Store Deployment'
          }
        }

        stage('Play Store') {
          steps {
            echo 'Play Store Deployment'
          }
        }

      }
    }

  }
}