pipeline {
  agent any

  // options {
  //   timestamps()
  // }

  stages {
    stage('Build') {
      options {
        timestamps()
      }

      steps {
        echo 'Hello World in Build'
        echo 'Hello World in Build Again'
      }
    }

    stage('Build with timestamp alternative') {
      steps {
        timestamps {
          echo 'Hello World in Build Alternative'
          echo 'Hello World in Build Alternative Again'
        }
      }
    }

    stage('Test') {
      steps {
        echo 'Hello World in Test'
        echo 'Hello World in Test Again'
      }
    }
  }
}
