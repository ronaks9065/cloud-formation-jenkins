pipeline
{
    agent any
    stages
    {
        stage('Submit Stack')
        {
              sh "aws cloudformation create-stack --stack-name s3bucket --template-body file://test.yml --region 'ap-south-1'"
        }
    }
}
