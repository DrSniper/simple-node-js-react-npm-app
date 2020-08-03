pipeline {
  agent any
  stages {
    stage('git clone') {
      steps {
        sh 'date'
      }
    }

    stage('mvn') {
      steps {
        sh 'echo 1111'
      }
    }

    stage('deploy') {
      steps {
        sh 'echo 22222'
      }
    }

    stage('end') {
      steps {
        sh 'time'
      }
    }

  }
}