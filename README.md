# 🌦 Weather Service – GitOps & Kubernetes Demo

This project is a **Weather Service (Fake API)** built to demonstrate a complete  
**DevOps & GitOps workflow** using Docker, Kubernetes, and Argo CD on AWS EC2.

> 🎯 Focus: Infrastructure, deployment flow, and GitOps concept  
> not application complexity.

---

## 📊 Architecture Diagram

######

---

## 🧱 Architecture Overview

```text
Client
  → NodePort Service (30080)
    → Kubernetes (k3s on EC2)
      → Weather Service Pod (Node.js)

GitHub (Manifests Repo)
  → Argo CD (GitOps Auto Sync)
    → Kubernetes Cluster
