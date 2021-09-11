pipeline {
    agent any
    stages {
        stage('Submit Stack1') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3bucket1 --template-body file://simplests3cft.json --region 'us-west-1'"
              }
             }
            }
            }
