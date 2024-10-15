pipeline {
    agent any

    stages {
        stage('lint and format') {
            parallel {
                stage('linting') {
                    steps {
                        echo "linting code in nested stage"
                    }
                }
                stage('formatting') {
                    steps {
                        echo "formatting code in nested stage"
                    }
                }
            }
        }
    }
}
