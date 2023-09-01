pipeline {
  agent any
  stages {
    stage('Fluffy Build') {
      steps {
        sh 'bash ./jenkins/build.sh'
      }
    }

    stage('Buzz Test') {
      steps {
        sh 'echo "test"'
      }
    }

  }
}