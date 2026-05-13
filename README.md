# 🚀 Real-Time Chat Application

![Forks](https://img.shields.io/github/forks/aadeshjagtap/my-project?style=social)
![Stars](https://img.shields.io/github/stars/aadeshjagtap/my-project?style=social)

---

## 👨‍💻 Owner
**Adesh Jagtap (@aadeshjagtap)**

---

## 📌 Overview

This is a full-stack real-time chat application built with modern technologies and DevOps practices like CI/CD, Docker, Kubernetes, and Monitoring.

It demonstrates how a production-like application is built, containerized, tested, and deployed using automation tools.

---

## ✨ Features

- ⚡ Real-time messaging using Socket.io  
- 🔐 JWT Authentication & Authorization  
- 👤 User profile management  
- 🟢 Online / Offline status tracking  
- 📱 Responsive UI  
- 🐳 Docker containerization  
- ☸️ Kubernetes deployment ready  
- 🔄 CI/CD automation using GitHub Actions  
- 📊 Monitoring with Prometheus & Grafana  

---

## 🧰 Tech Stack

### Backend
- Node.js
- Express
- MongoDB
- Socket.io

### Frontend
- React
- TailwindCSS
- Zustand

### DevOps
- Docker
- Kubernetes
- GitHub Actions
- Jenkins
- Nginx

## Kubernetes Deployment

```plaintext id="arch1"

Docker Images
      ↓
Kubernetes Deployment
      ↓
Pods Running
      ↓
Service Exposed
      ↓
Application Accessible

---

## CI/CD Pipeline

Every push to `main` triggers:

GitHub Push (Developer)
        ↓
GitHub Actions Trigger
        ↓
Build Docker Images (Frontend + Backend)
        ↓
Run Container Tests
        ↓
Deploy to Kubernetes Cluster
        ↓
Application Running

---

## System Architecture

User Browser
     ↓
Frontend (React)
     ↓
Backend API (Node.js + Express)
     ↓
MongoDB Database
     ↓
Socket.io (Real-time messaging)

---

## Monitoring & Logging

Application (Backend)
        ↓
Prometheus (Metrics Collection)
        ↓
Grafana (Dashboard Visualization)
        ↓
Logs (System Debugging)


---

## 🖥️ Quick Commands (For Setup & Run)

## 1. Clone Repository
```bash
git clone https://github.com/aadeshjagtap/my-project.git
cd my-project

## 2. Run using Docker
# Run Application
docker-compose up --build

# Open Application
http://localhost:8080

# Stop Application
docker-compose down

## 3. Kubernetes Setup
# Apply manifests
kubectl apply -f app-deployment/k8s/

# Check pods
kubectl get pods

# Check services
kubectl get svc

## 4. Trigger CI/CD
git add .
git commit -m "update"
git push origin main

# Access Application
http://localhost:8080
