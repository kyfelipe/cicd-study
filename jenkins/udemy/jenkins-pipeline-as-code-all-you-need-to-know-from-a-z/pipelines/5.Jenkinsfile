pipeline {
  agent any

  stages {
    stage('Build') {
      options {
        retry(3)
      }

      steps {
        echo 'Before settings current build to FAILURE'
        script {
          currentBuild.result = 'FAILURE'
        }
        error 'After setting current build to FAILURE'
      }
    }
  }
}
