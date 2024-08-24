pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3Stack --template-body file://cft-s3.yaml --region 'us-west-2'"
              }
             }
            }
            }
