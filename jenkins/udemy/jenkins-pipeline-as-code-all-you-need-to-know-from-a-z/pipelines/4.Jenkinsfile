pipeline {
  agent any

  stages {
    stage('Build') {
      tools {
        maven 'maven3.8.3'
      }

      steps {
        sh 'mvn --version'
      }
    }
  }
}
