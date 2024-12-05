pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                git 'https://github.com/ara9154vindu/Terraform_CICD.git'
            }
        }
        stage('init') {
            steps {
                sh 'terraform init'
            }
        }
    }
}
