pipeline {
    agent any

    environment {
        some_name = 'john'
    }

    stages {
        stage('Build') {
            when {
                not {
                    equals expected: 'jeff', actual: some_name
                }
            }

            steps {
                echo "${some_name}"
            }
        }
    }
}
