pipeline {
    agent any
    
    stages {
        stage('Checkout and Git Log') {
            steps {
                script {
                    checkout scm
                    sh 'git log'
                }
            }
        }
    }
}
