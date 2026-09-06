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

## 🏗️ Architecture
<br>
<br>
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/e3ac8dde-67f9-45e1-a743-ae592e49279a" />

The project is divided into two main environments:

- 🔄 **CI/CD & Security** — GitLab, Docker, GitLab SAST, Semgrep and Trivy.
- ☸️ **Runtime & Monitoring** — k3s, Argo CD, Prometheus, Grafana and Alertmanager.


## 📸 Project Screenshots
<br>
<br>

<img width="1586" height="791" alt="Capture d&#39;écran 2026-09-06 102556" src="https://github.com/user-attachments/assets/8d066b8b-a7e7-41a6-9b77-67dfe27ae17a" />

<br>
<br>

<img width="676" height="428" alt="Capture d&#39;écran 2026-09-05 112725" src="https://github.com/user-attachments/assets/ab1a4ed0-97c5-4908-b2ad-329fabd15c4c" />

<br>
<br>

<img width="1097" height="207" alt="Capture d&#39;écran 2026-09-05 123657" src="https://github.com/user-attachments/assets/d0262e01-35cf-4482-b449-8a060540f616" />

<br>
<br>

<img width="738" height="365" alt="Capture d&#39;écran 2026-07-19 100810" src="https://github.com/user-attachments/assets/3593bf6b-8eb9-49d6-9270-3d7f658660be" />

<br>
<br>

<img width="1497" height="675" alt="Capture d&#39;écran 2026-09-05 123950" src="https://github.com/user-attachments/assets/c98fe507-3030-463a-b294-653b53fa0c15" />


