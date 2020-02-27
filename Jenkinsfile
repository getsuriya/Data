pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        sh 'echo \'stage 1\''
        sh 'echo \'stage 2\''
      }
    }

    stage('stage 2') {
      steps {
        sleep 2
      }
    }

    stage('stage 3') {
      steps {
        sh 'echo \'completed\''
      }
    }

  }
}