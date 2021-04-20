Kubernetes on Cloud with Terraform and Wordpress with EFS
This repository helps to spin up cloud environment and create EKS cluster on AWS using terraform.

Prerequisites
Linux machine or Mac Os Machine
AWS Account

Usage
Update the aws account details in terrform varaiable file, then run the below command to install EKS Cluster

To clean up the AWS environment with kubernetes, run the below command

cd terrform/aws
terraform destroy -auto-approve