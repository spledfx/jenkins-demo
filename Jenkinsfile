pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                aws ec2 describe-instances --instance-ids i-0734f847eee42c09e --region eu-west-1
            }
        }
        
    }
}
