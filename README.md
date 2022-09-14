# Nodejs_myapp_k8_templates
Nodejs my-app files and kubernetes templates (project)

#### docker_nodeapp_image
* Contains nodejs application files and Dockerfile used to build Docker Image
* Image built is stored in AWS ECR and used in AWS ECS and EKS
* Contains docker-compose file for testing the built Docker image by deploying it on a docker network

#### myapp_k8_templates
* Contains kubernetes templates used to deploy the application locally (using minikube - testing) and in AWS EKS