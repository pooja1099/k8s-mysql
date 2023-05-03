Deploying MySQL on Kubernetes Cluster.

in this repo we learn about how to deploy MySQL Database on kubernetes cluster

1. install kubectl and mysql
2. run command as  follow;
   kubectl apply -f deployment.yaml
   
   kubectl apply -f service.yaml
   
   kubectl apply -f secrets.yaml
4.  run command:

   kubectl get pods
   
   kubectl exec --stdin --tty <pod_name> -- /bin/bash 
   
5. then it shows you like this:  
   root@pooja-deployment-95cc649b-fqrk6:/#
   run command: mysql -p
6. now enter password 
7. now your databse is ready to use
   mysql>
