# 🚀 Three-Tier Application Deployment on Kubernetes

## 📖 Overview
This project demonstrates the deployment of a **three-tier application** using **Docker and Kubernetes**, focusing on scalability, reliability, and production-ready infrastructure.

---

## 🏗️ Architecture
User → Ingress → Frontend → Backend → Database

- Ingress handles external traffic  
- Services enable internal communication  
- Database uses persistent storage  

---

## ☸️ Kubernetes Components
- Deployment – manages pods and scaling  
- Service – internal communication  
- Ingress – external access  
- Persistent Volume (PV) & Persistent Volume Claim (PVC) – storage  
- Secrets – secure configuration  

---

## 🐳 Containerization
- Applications are containerized using Docker  
- Lightweight images ensure consistency across environments  

---

## ⚙️ Deployment Summary
- Database deployed with persistent storage and secrets  
- Backend connected to database via internal service  
- Frontend exposed externally using Ingress  

---

## 🌐 Traffic Flow
1. User request → Ingress  
2. Frontend → Backend API  
3. Backend → Database  
4. Response → User  

---

## 📦 Key Features
- Scalable architecture  
- Container-based deployment  
- Persistent storage  
- Secure configuration  
- Kubernetes orchestration  
