After installing the pre-requisites:

1. Create a Cluster in the AWS EKS using the below command. Here I created a Cluster with serverless compute "FARGATE".
$ eksctl create cluster --name <cluster_name> --region <specify_region> --fargate

2. After done with the deployment for deleting the created Cluster use the below command:
$ eksctl delete cluster --name <cluster_name> --region <specify_region>

