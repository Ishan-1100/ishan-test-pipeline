pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
                withCredentials(credentialsId: '5150bf70-90ea-48e9-8553-913b61ef2f4f' ) {
                sh "aws cloudformation create-stack --stack-name s3Stack --template-body file://cft-s3.yaml --region 'us-west-1'"
                }
            }
        }
    }
}
