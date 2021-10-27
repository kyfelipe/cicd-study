pipeline {
  agent any

  stages {
    stage('Build') {
      options {
        timeout(time: 1, unit: 'SECONDS')
      }

      steps {
        echo 'Hello World'
        sleep 2
      }
    }
  }
}
