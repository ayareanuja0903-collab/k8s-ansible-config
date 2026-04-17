# 🚀 Kubernetes Ansible Configuration (k8s-ansible-config)

## 📌 Overview
This project provides **Ansible automation for configuring Kubernetes worker nodes** as part of a cloud-native DevOps/GitOps platform. It prepares EC2 instances (or any Linux nodes) with all required dependencies for joining a Kubernetes cluster and supports monitoring integration.

It is designed to work alongside:
- AWS EKS / kubeadm Kubernetes clusters
- Terraform infrastructure provisioning
- ArgoCD GitOps deployment pipelines
- Prometheus & Grafana monitoring stack

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

## 📂 Project Structure

k8s-ansible-config/
│
├── 📄 inventory.ini              # Target worker nodes
├── 📄 ansible.cfg                # Ansible configuration file
│
├── 📁 playbooks/                 # Ansible playbooks
│   ├── setup-docker.yml         # Docker / containerd installation
│   ├── k8s-prereq.yml           # Kubernetes prerequisites setup
│   ├── node-exporter.yml        # Monitoring agent setup
│
├── 📁 roles/                    # Reusable Ansible roles
│   ├── docker/                  # Docker role
│   ├── kubernetes/              # Kubernetes role
│   ├── monitoring/              # Monitoring role
│
├── 📁 images/                   # Architecture diagrams & screenshots
│   ├── architecture.png         # High-level system architecture
│   ├── ansible-flow.png         # Ansible execution flow
│   ├── kubernetes-cluster.png   # Cluster overview diagram
│
└── 📄 README.md                  # Project documentation
---
