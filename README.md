# Question-1
Create a Rabbit MQ deployment and service on which is exposed on 5672 and 15672 with a NodePort.  NodePort Mapping Requirements: ports 5672 to 31672  ports 15672 to 32000

Command to run the yaml file

kubectl apply -f rabbitmqdeployment.yaml
 
to check pods

kubectl get pods

to check service

kubectl get svc
