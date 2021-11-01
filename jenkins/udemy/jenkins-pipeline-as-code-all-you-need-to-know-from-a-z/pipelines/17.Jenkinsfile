pipeline {
    agent any

    stages {
        stage('Build buildingTag') {
            when {
                changelog '.*CHANGELOG.*'
            }

            steps {
                echo 'Building changelog'
            }
        }
    }
}
