Kubernetes-End-To-End-Deployment

Deployed a Game in the AWS EKS Cluster and Exposed to the outside world.

Here is the steps I followed

    Installed and configured all pre-requisites which is mentioned in the pre-requisites file for doing this Project.
    Creat a EKS Cluster by following the EKS Creation file.
    Create a FARGATE profile and deploy the GAME as pods by following the two commands mentioned in 2048 Game as Pods file.
    Follow the commands in OIDC_and_ALB file for creating OIDC connetion and installing ALB controller.
    Finally, you can verify it to get the external IP and access the application from any browser.

