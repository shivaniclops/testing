pipeline {
    agent any

    environment {
        SERVER_CREDS = credentials('ec2-user')
    }

    stages {
        stage('Setup') {
            steps {
                echo "My creds: ${SERVER_CREDS}"
                echo "Username: ${SERVER_CREDS_USR}"
                echo "Username: ${SERVER_CREDS_PSW}"
            }
        }
    
        stage('Test') {
            steps {
                // echo "The Database username is: ${USERNAME} and the password is: ${PASSWORD}"
                echo "this is test stage"
            }
        }
    }
}
