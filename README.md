# 🚀 Kubernetes + Ansible Automation Project

![Kubernetes](https://img.shields.io/badge/Kubernetes-1.29-blue?logo=kubernetes)
![Ansible](https://img.shields.io/badge/Ansible-Automation-red?logo=ansible)
![Docker](https://img.shields.io/badge/Docker-Container-blue?logo=docker)
![AWS](https://img.shields.io/badge/AWS-EKS-orange?logo=amazon-aws)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Project Overview

This project automates the setup of a **Kubernetes cluster on AWS EKS worker nodes using Ansible**.

It provisions and configures:
- 🐳 Docker / containerd runtime
- ☸️ Kubernetes prerequisites
- 📊 Node Exporter for monitoring
- 🔁 Reusable Ansible roles for scalability

---

## 🏗️ Architecture
<p align="center">
  <img src="images/Architecture.png" width="800"/>
</p>

---

## ⚙️ Features

- 🔧 Automated Kubernetes worker node setup
- 🐳 Docker / containerd installation
- ☸️ Kubernetes prerequisites configuration
- 🔐 Kernel & system tuning for K8s
- 📊 Node Exporter installation for monitoring
- 📡 Ready for Prometheus scraping
- 🚀 GitOps-ready infrastructure integration

---

## 📦 Repository Structure

k8s-ansible-config/
│
├── inventory.ini
├── ansible.cfg
├── README.md
│
├── playbooks/
│   ├── setup-docker.yml
│   ├── k8s-prereq.yml
│   └── node-exporter.yml
│
├── roles/
│   ├── docker/
│   ├── kubernetes/
│   └── monitoring/
│
└── images/
    ├── architecture.png
    ├── ansible-flow.png
    └── kubernetes-cluster.png
    
---
