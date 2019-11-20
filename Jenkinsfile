pipeline {
    agent any
    stages {
        stage('SCM') {
            steps {
                git credentialsId: '71217990-0ebc-403d-aa14-345cc97d91ce', url: 'https://github.com/devendra1321/kolkata.git'
            }
        }
    }
}
