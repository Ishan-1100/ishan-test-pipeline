pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation deploy --template-body file://cft-s3.yaml  --stack-name my-s3-stack --region 'us-west-1'"
              }
             }
            }
            }
