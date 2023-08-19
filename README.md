CI and Deployment with AWS



GITHUB actions
if folder with app is frontend then create folder .github/workflows/deploy.yml next to main app folder

frontend/
.github/workflows/deploy.yml  >> required to run CI


SET ENV like DOCKER CREDS


in .github/deploy.yaml >> Remember to change 

1 application_name
2 environment_name
3 existing_bucket_name
4 region  AWS Elastic Beanstalk environment



BEANSTALK
1 Create Application
2 Create Environment
3 Create Environment
4 Platform > Docker running on 64bit Amazon Linux2



in github settings,general,actions add > dummy values and then replace them with proper values
1 AWS_ACCESS_KEY
2 AWS_SECRET_KEY
3 DOCKER_USERNAME
4 DOCKER_PASSWORD


