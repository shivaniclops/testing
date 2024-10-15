pipeline {
    agent any

    stages {
        stage('lint and format') {
            stages {
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
