pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
                withCredentials(bindings: [credentialsId: '5150bf70-90ea-48e9-8553-913b61ef2f4f']) {
                    sh "aws cloudformation deploy --template-body file://cft-s3.yaml --stack-name s3Stack  --region 'us-east-2'"
                }
            }
        }
    }
}
