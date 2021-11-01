pipeline {
    agent any

    environment {
        DEPLOY_ID = 'production'
    }

    stages {
        stage('Build') {
            when {
                environment name: 'DEPLOY_ID', value: 'production'
            }

            steps {
                echo 'Deploying'
            }
        }
    }
}
