## Command to connect to EKS Cluster

aws eks --region us-east-1 describe-cluster --name hiteshCluster --query cluster.status

aws eks --region us-east-1 update-kubeconfig --name hiteshCluster

kubectl get nodes
