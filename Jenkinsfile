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
                echo "This is test stage"
            }
        }
    }
}
