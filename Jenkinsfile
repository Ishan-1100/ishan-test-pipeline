pipeline {
    agent any
    environment {
    //     AWS_ACCESS_KEY_ID = 
    //     AWS_SECRET_ACCESS_KEY = 
    // }
    stages {
        stage('Submit Stack') {
            steps {
                    sh "aws cloudformation deploy --template-file cft-s3.yaml --stack-name s3Stack  --region 'us-east-1'"
            }
        }
    }
}
//withCredentials(bindings: [credentialsId: '5150bf70-90ea-48e9-8553-913b61ef2f4f'])
