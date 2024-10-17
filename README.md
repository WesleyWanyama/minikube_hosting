# Minikube Hosting and Argo CD

This project involves setting up a kubernetes cluster and also a sample configuration for deploying applications using Argo CD on the Minikube cluster. The kubernetes cluster consists of:

- A **React** frontend
- A **Spring Boot** API backend
- A **MySQL** database service

## Start Minikube
Start Minikube to create a local kubernetes cluster
```bash
minikube start
```

## Deployment
The following manifest files are for the purpose of creating the deployments:
1. React App: `react-deployment.yaml`
2. Spring Boot API: `spring-deployment.yaml`
3. Database: `mysql-deployment.yaml`

## Apply the Manifests
Apply the Kubernetes manifests to deploy the applications:
```bash
kubectl apply -f react-deployment.yaml
kubectl apply -f spring-deployment.yaml
kubectl apply -f mysql-deployment.yaml
```

## Install Argo CD
1. 






