1-create infrastructure <br>
• A GKE cluster with Linux Worker Nodes. <br>
•Load Balancer that routes external traffic to the Worker Nodes. <br>
•A NAT router that allows all our instances inside the VPC to access the internet. <br>
•A Bastion Instance that allows us to access the Kubernetes Control Plane to run kubectl CLI commands. This is basically just a Linux machine with a proxy installed on it. That is exposed to the internet via an external IP address. 
--------------------------------------------------------------------------------------------------------
2-connect to the cluster <br>
2.1 configure the Bastin vm to connect to the cluster  

     -install Kubectl 
     -install auth-plugin 
     -connect to cluster 
--------------------------------------------------------------------------------------------------------
3-Install jenkens using helm
-------------------------------------------------------------------------------------------------------
4-deploy application on cluster 
--------------------------------------------------------------------------------------------
Reference used  

1-create infrastructure 

https://thoeny.dev/create-a-private-gcp-kubernetes-cluster-using-terraform 

2- Continuous deployment to GKE using Jenkins 

https://cloud.google.com/kubernetes-engine/docs/archive/continuous-delivery-jenkins-kubernetes-engine 

3- Continuous deployment to GKE using Jenkins (app) 

https://cloud.google.com/kubernetes-engine/docs/archive/continuous-delivery-jenkins-kubernetes-engine 

 
