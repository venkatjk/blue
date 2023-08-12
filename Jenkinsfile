pipeline {
  agent any
  stages {
    stage('DEv') {
      parallel {
        stage('DEv') {
          steps {
            echo 'Hello world'
          }
        }

        stage('test') {
          steps {
            sh 'date'
          }
        }

      }
    }

  }
}