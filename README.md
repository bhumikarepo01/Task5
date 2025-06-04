# Kubernetes Cluster with Minikube

## 📌 Task Overview
Built a local Kubernetes cluster using Minikube and deployed a sample NGINX application.

## 🛠 Tools Used
- Minikube
- kubectl
- Docker
- Git, GitHub

## 📂 Files Included
- `deployment.yaml`: Defines the NGINX deployment
- `service.yaml`: Exposes the deployment using NodePort
- `screenshots/`: Contains output of `kubectl get pods`, `kubectl get services`, and browser screenshot of NGINX

## 📸 Screenshots
Check the `/screenshots` folder for:
- `pods.png`
- `services.png`
- `nginx_browser.png`

## 🚀 Commands Used
- `minikube start`
- `kubectl apply -f deployment.yaml`
- `kubectl apply -f service.yaml`
- `kubectl get pods`
- `kubectl get services`
- `kubectl scale deployment hello-deployment --replicas=4`

## ✅ Status
Task Completed and Working!
