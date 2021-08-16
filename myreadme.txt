Full flow at - https://www.armory.io/blog/continuous-integration-using-jenkins-and-hashicorp-terraform-with-spinnaker-on-amazon-eks/

AWS -  https://aws.amazon.com/blogs/opensource/continuous-integration-using-jenkins-and-hashicorp-terraform-on-amazon-eks/


https://www.armory.io/blog/build-a-deployment-pipeline-with-spinnaker-on-kubernetes/


================================SETUP ON AMI LINUX=========================================================
sudo yum update
sudo yum install -y git
git clone https://github.com/aws-samples/amazon-eks-jenkins-terraform.git

aws configure

Install Terraform  
--------------------
sudo yum install -y yum-utils
sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/AmazonLinux/hashicorp.repo
sudo yum -y install terraform

