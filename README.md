# ContactBook Application

## 📌 Project Overview

This project demonstrates a fully automated DevOps CI/CD pipeline for deploying a ContactBook Maven application on AWS using Terraform, Ansible, Jenkins, Docker, Kubernetes, Prometheus, and Grafana.

The pipeline automates infrastructure provisioning, configuration management, containerization, deployment, and monitoring in a cloud environment.

---

## 🚀 Tech Stack

### Cloud Platform
- AWS EC2

### DevOps Tools
- Terraform
- Ansible
- Jenkins
- Docker
- Kubernetes (K3s)

### Monitoring Tools
- Prometheus
- Grafana

### Application Stack
- Java
- Maven
- ContactBook Web Application

---

## ⚙️ Features

- Automated AWS infrastructure provisioning
- Dynamic inventory with Ansible
- Automated CI/CD pipeline using Jenkins
- Docker containerization
- Kubernetes deployment orchestration
- Monitoring with Prometheus
- Dashboard visualization using Grafana
- Fully automated cloud deployment

---

## 🏗️ Architecture Flow

GitHub → Jenkins → Terraform → Ansible → Docker → Kubernetes → Prometheus → Grafana

---

## 📊 Monitoring

- Application metrics scraping using Prometheus
- Grafana dashboards for visualization
- Kubernetes monitoring integration

---

## 🐛 Problems Solved During Development

- Docker architecture compatibility issue (ARM vs AMD64)
- Prometheus scrape configuration issue
- Grafana dashboard provisioning issue
- Kubernetes pod explosion issue

---

## 📄 Detailed Documentation

See `Project_Report.pdf` for:
- Architecture diagrams
- Pipeline screenshots
- Kubernetes deployment
- Monitoring dashboards
- Troubleshooting steps
