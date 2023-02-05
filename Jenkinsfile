pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'pwd '
          }
        }

        stage('Build1') {
          steps {
            sh 'hostname'
          }
        }

      }
    }

    stage('Test') {
      steps {
        sh 'date'
      }
    }

  }
}