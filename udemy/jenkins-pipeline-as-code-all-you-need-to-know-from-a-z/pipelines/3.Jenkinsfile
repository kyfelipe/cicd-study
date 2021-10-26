pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        retry(3) {
          // unit: DAYS, HOURS, MINUTES, SECONDS, MILISECONDS, MICROSECONDS
          timeout(time: 1, unit: 'SECONDS') {
            sleep 2
          }
          
          echo 'after timeout'
        }
      }
    }
  }
}
