pipeline {
    agent any 
    stages{
          stage('deploy to S3'){
              steps{
                  sh 'aws s3 cp . s3://mywebsite-123'
              }
          }
      }
}
