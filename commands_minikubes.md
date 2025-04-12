## Start minkube
minikube start --force

## Metrics server
##### to enable CAdvisor
minikube addons enable metrics-server

##### To test the logs
docker run -d kodekloud/event-simulator


