import groovy.transform.Field
org.jenkinsci.plugins.pipeline.modeldefinition.parser.RuntimeASTTransformer.SCRIPT_SPLITTING_TRANSFORMATION=true 

pipeline {
    agent any
pipeline {
    agent any
    stages {
        stage('deploy') {
            steps {
              sh "aws configure set region $AWS_DEFAULT_REGION" 
              sh "aws configure set aws_access_key_id $AWS_ACCESS_KEY_ID"  
              sh "aws configure set aws_secret_access_key $AWS_SECRET_ACCESS_KEY"
              sh "aws s3 cp . s3://beginner-html-site-styled"
            }
        }
    }
}
