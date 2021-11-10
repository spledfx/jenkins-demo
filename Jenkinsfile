pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh "aws cloudformation deploy --template-file awsbackup.yaml --stack-name my-new-stack --region eu-west-1"
            }
        }       
    }
}
