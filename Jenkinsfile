pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        sh '''mkdir -pv test_pipline 
pwd'''
      }
    }

    stage('error') {
      steps {
        sh 'ls -lrsh'
      }
    }

  }
}