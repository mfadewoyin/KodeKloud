# KodeKloud

 Task carried  out on kodekloud Engineers 

 Deploy Node App on Kubernetes
 Create a namespace named node-namespace-xfusion.

Create a deployment named node-deployment-xfusion under this new namespace. Replica count should be 2, container should be named as node-container-xfusion, use gcr.io/kodekloud/centos-ssh-enabled:node image and container port should be 80.

Create a service named node-service-xfusion. Service type should be NodePort, target port should be 8080, port should be 80 and nodePort should be 30012.

Make sure all pods are in Running state after the deployment.

You can check the application page by clicking on + button on top left corner and clicking on Select port to view on Host 1, then enter your nodePort.

You can use any labels as per your choice.

Note: The kubectl on jump_host has been configured to work with the kubernetes cluster.
