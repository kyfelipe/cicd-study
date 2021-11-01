pipeline {
    agent any

    stages {
        stage('Build buildingTag') {
            when {
                buildingTag()
            }

            steps {
                echo 'Building buildingTag'
            }
        }

        stage('Build tag') {
            when {
                tag '2.0'
            }

            steps {
                echo 'Building tag'
            }
        }
    }
}
