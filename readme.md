# Proactive Monitoring for Continuous Availability

This project implements a proactive monitoring system using **Flask**, **Docker**, **Kubernetes**, and **IBM Cloud**.

## 🚀 Features
- Real-time CPU & Memory monitoring
- Containerized with Docker
- Deployed on IBM Cloud Kubernetes Service
- Automated CI/CD with Jenkins

## 📦 Setup & Deployment
```sh
git clone https://github.com/Sriya-Satish/Proactive-Monitoring
cd proactive-monitoring
docker build -t monitoring-app .
docker run -p 5000:5000 monitoring-app