pipeline {
  agent {
    node {
      label 'my_app'
    }

  }
  stages {
    stage('BuildIngesoftLab4') {
      parallel {
        stage('BuildIngesoftLab4') {
          steps {
            echo 'Hello'
          }
        }

        stage('Check Pubspec.yaml') {
          steps {
            fileExists 'pubspec.yaml'
          }
        }

      }
    }

    stage('Testing') {
      steps {
        echo 'Testeando'
      }
    }

  }
}