# AWS-CI-CD : End to End MAchine Learning Project

- Docker Build checked
- Github Workflow
- Iam User In AWS
  
 ## Docker Setup In EC2 commands to be Executed

 #optional

sudo apt-get update -y

sudo apt-get upgrade

 #required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker

## Configure EC2 as self-hosted runner:

Setup github secrets:

AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION = 

AWS_ECR_LOGIN_URI = 

ECR_REPOSITORY_NAME = 


Shoutout to Krish Naik from whom this tutorial comes from. My first step into the MLOps field is from him so go check his github: https://github.com/krishnaik06
