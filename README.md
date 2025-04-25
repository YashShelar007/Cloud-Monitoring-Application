# ☁️ Cloud Monitoring Application – AWS-Powered Deployment Tracker

A lightweight dashboard that monitors EKS and ECR activity on AWS using Python automation and Docker, designed for real-time container visibility and DevOps readiness.

### 🔗 GitHub Repo: https://github.com/YashShelar007/Cloud-Monitoring-Application

---

## 📍 Problem It Solves

Monitoring container and cluster health across AWS EKS/ECR can be manual and siloed. This tool centralizes real-time deployment stats, simplifying infrastructure visibility for developers and SREs.

---

## ✨ Key Features

- ✅ Real-time visibility into AWS EKS cluster status
- ✅ ECR image inspection and lifecycle management
- ✅ Dockerized Flask app for easy deployment
- ✅ Basic HTML dashboard using Jinja templates

---

## 🛠 Tech Stack

- **Backend**: Python, Flask
- **Cloud**: AWS EKS, AWS ECR
- **Infra**: Docker, Boto3, Shell Scripting
- **UI**: Jinja2 Templates, HTML5

---

## 🧠 Architecture

```
[User] → [Flask App (app.py)]
        → [EKS & ECR Scripts]
        → [AWS Boto3 SDK]
        → [Docker Dashboard + HTML]
```

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/YashShelar007/Cloud-Monitoring-Application.git
cd Cloud-Monitoring-Application/cloud-monitoring-application

# Build the Docker image
docker build -t cloud-monitor .

# Run the container
docker run -p 5000:5000 cloud-monitor
```

---

## 🔐 Prerequisites

- AWS CLI configured (`aws configure`)
- IAM permissions for EKS & ECR
- Docker installed and running

---

## 🧩 Future Enhancements

- 📊 Add real-time graphs for EKS node health
- 📦 Show full ECR image history with tags
- 🔒 Integrate login/auth for admin-only access

---

## 👨‍💻 Author

**Yash Shelar**  
Portfolio: [yashshelar.com](https://yashshelar.com)  
LinkedIn: [linkedin.com/in/shelar-yash](https://linkedin.com/in/shelar-yash)
