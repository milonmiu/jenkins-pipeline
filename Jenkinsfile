pipeline {
    agent any
    parameters {
        choice(name: 'ENV', choices: ['dev', 'stage', 'prod'], description: 'Select Environment')
        string(name: 'TAG', defaultValue: 'v1.0', description: 'Enter Version Tag')
    }
    stages {
        stage('Deploy') {
            steps {
                echo "Selected Environment: ${params.ENV}"
                echo "Version Tag: ${params.TAG}"
            }
        }
    }
}
