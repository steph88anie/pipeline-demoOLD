pipeline {
  agent any
  stages {
    stage('Buzz Buzz') {
      agent any
      steps {
        sh './jenkins/build.sh'
      }
    }
    stage('Buzz Test') {
      steps {
        sh './jenkins/test-all.sh'
      }
    }
  }
}