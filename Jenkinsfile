pipeline {
  agent any
  stages {
  stage('Build') {
  steps {
   sh label: '', script: 'mvn package'
  archiveArtifacts artifacts: '**/target/*.jar', fingerprint: true 
  }
  }
  }
}
