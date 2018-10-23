pipeline {
  agent any
  stages {
    stage('compile') {
      parallel {
        stage('compile') {
          steps {
            sleep 1
          }
        }
        stage('123') {
          steps {
            sleep 1
          }
        }
      }
    }
    stage('test') {
      steps {
        echo 'hello'
      }
    }
  }
}