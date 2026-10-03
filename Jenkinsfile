pipeline {
    agent any
    environment {
        APP_ENV = 'production'
    }
    stages {
        stage('Build') {
            steps {
                echo "Deploying to ${env.APP_ENV}"
            }
        }
    }
}

