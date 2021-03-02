pipeline {
    agent any
    stages {
        stage('Init') {
            steps {
                echo 'Init'
                sh 'cp **/* .'
                sh 'terraform init'
                
            }
        }
       
    }
}
