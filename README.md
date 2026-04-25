# Ansible Roboshop Automation 🚀

## 📌 Repository Description

This repository contains Ansible playbooks and configuration files to provision, configure, and deploy the Roboshop microservices application.

It demonstrates real-world DevOps automation using Ansible for application services, databases, messaging systems, web servers, and AWS infrastructure components.

---

## 📌 Project Overview

Roboshop is a microservices-based e-commerce application used widely for DevOps practice.

This repository automates the setup of:

- Application Services
- Databases
- Web Server
- Message Queue
- Cache Layer
- AWS Infrastructure Components

---

## 🛠 Technologies Used

- Ansible
- YAML
- Linux
- AWS EC2
- Route53
- Nginx
- MongoDB
- MySQL
- Redis
- RabbitMQ

---

## 📂 Repository Structure

```bash
ansible-roboshop/
│── 01-ec2-r53.yaml
│── ansible.cfg
│── inventory.ini
│
│── cart.yaml
│── cart.service
│
│── catalogue.yaml
│── catalogue.service
│
│── frontend.yaml
│── frontend.aws_ec2.yaml
│── nginx.conf
│── nginx.yaml
│
│── mongodb.yaml
│── mongo.repo
│
│── mysql.yaml
│
│── payment.yaml
│── payment.service
│
│── rabbitmq.yaml
│── rabbitmq.repo
│
│── redis.yaml
│
│── shipping.yaml
│── shipping.service
│
│── user.yaml
│── user.service
```
---
## ⚙️ Services Automated

# Frontend
- Nginx installation
- Reverse proxy configuration
- Frontend deployment

# Backend Microservices
- Cart
- Catalogue
- Payment
- Shipping
- User

# Databases
- MongoDB
- MySQL

# Cloud Components
- AWS EC2 provisioning
- Route53 DNS configuration

---

## 🚀 How to Run

Configure Inventory

```bash
vi inventory.ini
```

## Run Specific Service Playbook

Run Specific Service Playbook

```bash
ansible-playbook -i inventory.ini cart.yaml
```

## Run Frontend Setup

```bash
ansible-playbook -i inventory.ini frontend.yaml
```

## Run Database Setup

```bash
ansible-playbook -i inventory.ini mongodb.yaml
ansible-playbook -i inventory.ini mysql.yaml
```
---

## 🎯 Key Features
- Infrastructure as Code using Ansible
- Repeatable server provisioning
- Multi-service automation
- Real-time DevOps project structure
- Production-style configuration management

---

## 📈 Use Cases
- DevOps Interview Preparation
- Learning Ansible Hands-on
- Multi-tier Application Deployment
- Server Configuration Automation
- AWS Infrastructure Practice

---

## 👨‍💻 Author

Surendra.

DevOps Engineer

---

⭐ If you like this project, give it a star.