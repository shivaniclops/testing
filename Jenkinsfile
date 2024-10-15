pipeline {
    agent any

    stages {
        stage('lint and format') {
            stages{
                stage('linting'){
                    steps{
                        echo "listing code in nested stage"
                    }
                }
            }
            stages{
                stage('formatting'){
                    steps{
                        echo "formatting code in nested stage"
                    }
                }
            }
        }
    }
}
