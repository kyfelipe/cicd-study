pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        retry(3) {
          // unit: DAYS, HOURS, MINUTES, SECONDS, MILLISECONDS, MICROSECONDS
          timeout(time: 1, unit: 'SECONDS') {
            sleep 2
          }

          echo 'after timeout'
        }
      }
    }
  }
}
