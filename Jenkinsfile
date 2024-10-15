pipeline {
    agent any

    stages {
        stage('lint and format') {
            parallel {
                stage('linting') {
                    steps {
                        sh "sleep 30"
                    }
                }
                stage('formatting') {
                    steps {
                        sh "sleep 30"
                    }
                }
            }
        }
    }
}
