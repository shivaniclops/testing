pipeline {
    agent any

    environment {
        DB_HOST  = '192.168.12.2'
        USERNAME = 'Admin'
        PASSWORD = 'Admin@123'
    }

    stages {
        stage('Setup') {
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
