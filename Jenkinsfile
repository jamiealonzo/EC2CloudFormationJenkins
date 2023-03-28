pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name jamieEC2 --template-body file://01_ec2.yaml --region 'us-east-1'"
              }
         }


     }
}
