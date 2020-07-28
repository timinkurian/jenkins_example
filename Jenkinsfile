pipeline {
  agent any
  stages {
    stage('First') {
      parallel {
        stage('First') {
          steps {
            echo 'pipeline started'
          }
        }

        stage('Second') {
          steps {
            echo 'This is the second step'
          }
        }

        stage('step') {
          steps {
            sh 'maven -version'
          }
        }

      }
    }

  }
}