pipeline {
  agent any
  stages {
    stage('ver') {
      steps {
        echo 'testing'
      }
    }
    stage('otro') {
      parallel {
        stage('otro') {
          steps {
            pwd(tmp: true)
          }
        }
        stage('dfdfd') {
          steps {
            waitUntil()
          }
        }
      }
    }
  }
}