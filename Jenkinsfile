pipeline {
    agent any

    stages {
        stage('initialise') {
            steps {
                sh 'terraform init'
            }
        }
        stage('format') {
            steps {
                sh 'terraform fmt'
            }
        }
         stage('validate') {
            steps {
                sh 'terraform validate'
            }
        }
         stage('plan') {
            steps {
                sh 'terrafonrm plan'
            }
        }
         stage('apply') {
            steps {
                sh 'terrafonrm apply'
            }
        }
    }
}
