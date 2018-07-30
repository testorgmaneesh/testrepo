pipeline {
    agent { label 'master'}
    stages {
        stage('Terraform Setup') {
            steps {
                sh "echo step1"
            }
        }
        stage('Docker Registry Setup') {
            steps {
                sh "echo step2"
            }
        }
    }
}
