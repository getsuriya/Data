pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        sh 'echo \'hello 1\''
        sh 'echo \'stage 2\''
      }
    }

    stage('stage 2') {
      steps {
        sleep 1000
      }
    }

    stage('stage 3') {
      steps {
        sh 'echo \'bye\''
      }
    }

  }
}