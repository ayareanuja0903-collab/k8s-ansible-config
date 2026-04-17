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

------

## ⚙️ Ansible Workflow

<p align="center">
  <img src="images/Ansible%20execution%20flowchart%20diagram.png" width="800"/>
</p>

---

## ☸️ Kubernetes Cluster Overview

<p align="center">
  <img src="images/Kubernetes%20cluster%20architecture.png" width="800"/>
</p>

---

## 📦 Repository Structure

```bash
inventory.ini        # EC2 / worker node inventory
ansible.cfg          # Ansible configuration
playbooks/           # Main automation playbooks
roles/               # Reusable roles (Docker, K8s, Monitoring)
images/              # Architecture diagrams

```

## ⚙️ Features

- 🔧 Automated Kubernetes worker node setup
- 🐳 Docker / containerd installation
- ☸️ Kubernetes prerequisites configuration
- 🔐 Kernel & system tuning for K8s
- 📊 Node Exporter installation for monitoring
- 📡 Ready for Prometheus scraping
- 🚀 GitOps-ready infrastructure integration

---
