pipeline {
  agent any
  stages {
  stage('Build') {
  steps {
  sh 'make' ①
  archiveArtifacts artifacts: '**/target/*.jar', fingerprint: true ②
  }
  }
  }
}
