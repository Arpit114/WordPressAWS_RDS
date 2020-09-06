# WordPressAWS_RDS
This repo contains the Terraform code for deploying WordPress on the top of Minikube with MySQL Database launched on AWS RDS . 
Some key requirements :
a. Minikube should be installed in your system and configured .
b. Terraform should be installed and environment variable set .
c. Should have an AWS account and AWS CLI been configured in your system .
d. Create a profile using aws configure and set that profile in the code also , else , set the pre-created profile in the code.
e. Better to launch the Wordpress once before running this code in your system . Launch wordpress using command : 
# kubectl run wp --image=wordpress
: will take time accoe=rding to your internet speed as the image will be pulled from dockerhub .
f. download the code and run the following commands..
# terraform init
# terraform apply --auto-approve
