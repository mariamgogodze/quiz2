pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('Test') {
          steps {
            sleep 2
          }
        }

        stage('Error') {
          steps {
            sleep 2
          }
        }

      }
    }

  }
}