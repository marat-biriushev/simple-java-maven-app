pipeline {
  agent any
  stages {
    stage('Fluffy Build') {
      steps {
        sh './jenkins/build.sh'
      }
    }

    stage('Buzz Test') {
      steps {
        sh 'echo "test"'
      }
    }

  }
}