pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh "aws cloudformation deploy --template-file awsbackup.yaml --stack-name aws-backup-stack --region eu-west-1"
            }
        }       
    }
}
