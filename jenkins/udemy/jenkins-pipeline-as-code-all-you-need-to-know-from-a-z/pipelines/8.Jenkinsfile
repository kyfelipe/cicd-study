pipeline {
    agent any

    environment {
        name1 = 'Jeff'
        name2 = 'John'
    }

    stages {
        stage('Build') {
            environment {
                name2 = 'Mike'
                name3 = 'Jamie'
                SOME_SECRET = credentials('some_secret')
            }

            steps {
                echo "name1 ${name1}"
                echo "name2 ${name2}"
                echo "name3 ${name3}"
                echo "SOME_SECRET ${SOME_SECRET}"
            }
        }
    }
}
