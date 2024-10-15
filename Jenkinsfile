pipeline {
    agent any

    stages {
        stage('Setup') {
            steps {
                withCredentials([usernamePassword(credentialsId: 'ec2-user', usernameVariable: 'myuser', passwordVariable: 'mypassword')]) {
                
                sh '''
                echo ${myuser}
                echo ${mypassword}
                '''
            }
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
}
