# kops-cluster

Kubernetes on AWS using Kops
1. Launch Linux EC2 instance in AWS (Kubernetes Client)
2. Create and attach IAM role to EC2 Instance.
  
   Kops need permissions to access
	    S3
	  EC2
	  VPC
	  Route53
	  Autoscaling
	  etc..
