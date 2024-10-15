pipeline {
    agent any
    
    stages {
        stage('Setup') {
        environment {
            DB_HOST  = '192.168.12.2'
            USERNAME = 'Admin'
            PASSWORD = 'Admin@123'
        }
            steps {
                echo "The Database IP is: ${DB_HOST}"
            }
        }
    
        stage('Test') {
            steps {
                echo "Commit: ${env.GIT_COMMIT}
            }
        }
    }
}
