# ⚙️ DevSecOps CI/CD & Kubernetes Platform

## 🎯 Objective

The main objective of this project is to build an **automated and secure DevSecOps pipeline** for continuous integration, deployment, and monitoring of containerized applications.

The project aims to:

- 🔹 **Automate the CI/CD process** from code changes to application deployment.
- 🔹 Integrate **security checks** into the pipeline to detect code vulnerabilities, container vulnerabilities, and exposed secrets.
- 🔹 **Automatically deploy applications** to Kubernetes using **Argo CD and GitOps**.
- 🔹 Enable **automatic rollback to a previous stable version** when a deployment fails or an issue is detected.
- 🔹 **Monitor applications and infrastructure** using Prometheus, Grafana, and Alertmanager.

## 🛠️ Technologies

### 🔄 CI/CD & Containerization

- 🦊 **GitLab** — Source code management & CI/CD
- 🐳 **Docker** — Containerization

### 🔐 Security

- 🔍 **GitLab SAST** — Static Application Security Testing
- 🧪 **Semgrep** — Static code security analysis
- 🛡️ **Trivy** — Docker image vulnerability scanning

### ☸️ Deployment & Monitoring

- ☸️ **k3s** — Lightweight Kubernetes cluster
- 🚀 **Argo CD** — GitOps & automated deployment
- 📈 **Prometheus** — Monitoring & metrics collection
- 📊 **Grafana** — Metrics visualization
- 🚨 **Alertmanager** — Alert management
