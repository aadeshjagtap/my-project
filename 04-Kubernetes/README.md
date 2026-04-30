Nginx Kubernetes Deployment 🚀

This project demonstrates a basic Kubernetes setup using YAML files.

📦 Components
Deployment (nginx)
Service (ClusterIP)
🚀 How to Run
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
🔗 Access
kubectl port-forward service/nginx-service 8080:80

Open: http://localhost:8080
