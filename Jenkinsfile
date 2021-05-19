pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/KAN19/hello-jenkins.git' 
            }
        }
         stage('Mail') {
            steps {
                mail bcc: '', body: 'Hello everyone', cc: '', from: '', replyTo: '', subject: 'Hello ', to: 'nguyenkiet0807@gmail.com'
            }
        }
    }
}