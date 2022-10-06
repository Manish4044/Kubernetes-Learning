## Topics covered
### kubectl main commands
kubectl create <component> NAME  
--Creates the yaml file and starts this in the cluster  
--Example: kubectl create deployment nginx-depl --image=nginx  
kubectl get pods | deployments | services | all  
--Gives status of different components running in the cluster  
kubectl describe <component> NAME  
kubectl edit <component> NAME  
--Allows to change in the yaml file of <component>  
