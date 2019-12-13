pipeline {
  agent any
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

        stage('Check falseFile.dart') {
          steps {
            fileExists 'falseFile.dart'
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