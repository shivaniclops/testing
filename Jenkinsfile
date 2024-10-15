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
                echo "The Database username is: ${USERNAME} and the password is: ${PASSWORD}"
            }
        }
    }
}
