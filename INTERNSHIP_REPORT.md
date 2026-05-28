
# 🚀 Configuration Management Using Ansible

## 📘 DevOps Internship Project Documentation

---

# 📌 Project Overview

The primary objective of the project is to automate:

✅ Server Configuration
✅ Application Deployment
✅ Web Server Setup
✅ Monitoring Configuration
✅ CI/CD Integration

using **Configuration Management tools** and modern DevOps practices.

---

# 🎯 Project Objectives

✔️ Automate server configuration using Ansible
✔️ Configure web servers using Nginx
✔️ Implement monitoring using Prometheus and Grafana
✔️ Reduce manual configuration effort
✔️ Implement CI/CD pipeline integration
✔️ Improve deployment consistency and automation

---

# 🛠️ Technologies Used

| Category                    | Tool                     |
| --------------------------- | ------------------------ |
| ☁️ Cloud Platform           | AWS EC2                  |
| ⚙️ Configuration Management | Ansible                  |
| 🌐 Web Server               | Nginx                    |
| 📊 Monitoring               | Prometheus & Grafana     |
| 🔧 Version Control          | Git & GitHub             |
| 🚀 CI/CD                    | GitHub Actions / Jenkins |
| 🐧 Operating System         | Ubuntu Server            |

---

# 📂 Project Structure

```bash
Configuration-Management-Using-Ansible/
│
├── ansible/
│   ├── inventory.ini
│   ├── Configration.yml
│
├── .github/
│   └── workflows/
│
├── screenshots/
│
├── README.md
```

---

# 📊 DevOps Architecture Diagram

```text
 ┌────────────────────────┐
 │ 👩‍💻 Developer          │
 │ Push Code to GitHub   │
 └──────────┬────────────┘
            │
            ▼
 ┌────────────────────────┐
 │ 🐙 GitHub Repository   │
 └──────────┬────────────┘
            │
            ▼
 ┌────────────────────────┐
 │ 🚀 CI/CD Pipeline      │
 │ GitHub Actions/Jenkins│
 └──────────┬────────────┘
            │
            ▼
 ┌────────────────────────┐
 │ ☁️ AWS EC2 Instances   │
 │ Infrastructure Setup  │
 └──────────┬────────────┘
            │
            ▼
 ┌────────────────────────┐
 │ ⚙️ Ansible Automation  │
 │ Configuration Mgmt    │
 └──────────┬────────────┘
            │
   ┌────────┼─────────┐
   ▼        ▼         ▼
┌────────┐ ┌────────┐ ┌────────────┐
│Install │ │Configure│ │ Deploy App │
│Packages│ │ Nginx   │ │ Application │
└────────┘ └────────┘ └────────────┘
            │
            ▼
 ┌────────────────────────┐
 │ 📊 Monitoring Stack    │
 │ Prometheus + Grafana  │
 └────────────────────────┘
```

---

# 🔄 Project Workflow

## 📌 Step 1 — Infrastructure Provisioning

AWS EC2 instances are created and configured to host applications and monitoring services.

---

## 📌 Step 2 — Configuration Management

Ansible automates server setup and configuration.

Tasks automated using Ansible:

✅ Install Required Packages
✅ Configure Nginx Web Server
✅ Deploy Application
✅ Configure Monitoring Tools

---

# 💻 Important Ansible Commands

## 🔍 Check Connectivity

```bash
ansible all -m ping -i inventory.ini
```

## 🚀 Run Playbook

```bash
ansible-playbook -i inventory.ini Configration.yml
```

---

# 📊 Monitoring Setup

The monitoring stack includes:

* 📈 Prometheus
* 📊 Grafana

Prometheus collects server metrics and Grafana visualizes those metrics using interactive dashboards.

---

# ⚙️ CI/CD Pipeline

The CI/CD pipeline automates:

✅ Infrastructure Provisioning
✅ Configuration Management
✅ Application Deployment
✅ Monitoring Setup

## Tools Used

* GitHub Actions
* Jenkins

---

# 🚀 How to Run the Project

# 📋 Prerequisites

Install the following tools:

* Ansible
* Git
* AWS CLI

---

# ⚙️ Setup Instructions

## 1️⃣ Clone Repository

```bash
git clone https://github.com/dipali-nagesh/Configuration-Management-Using-Ansible.git

cd Configuration-Management-Using-Ansible
```

---

## 2️⃣ Configure AWS Credentials

```bash
aws configure
```

---

## 3️⃣ Configure Inventory File

Update EC2 public IP addresses inside:

```bash
inventory.ini
```

---

## 4️⃣ Run Ansible Playbook

```bash
cd ansible

ansible-playbook -i inventory.ini Configration.yml
```

---

# 📦 Ansible Playbook Responsibilities

The playbook automates:

| Task                    | Description                    |
| ----------------------- | ------------------------------ |
| 📦 Package Installation | Install required software      |
| 🌐 Nginx Configuration  | Configure web server           |
| 🚀 Deployment           | Deploy application             |
| 📊 Monitoring Setup     | Configure Prometheus & Grafana |

---

# ✅ Advantages of Configuration Management

✨ Faster Deployment
✨ Reduced Manual Errors
✨ Consistent Environment Setup
✨ Scalable Infrastructure
✨ Easy Automation
✨ Improved Productivity

---

# 📚 Learning Outcomes

Through this project, the following concepts were learned:

✅ Configuration Management
✅ Automation using Ansible
✅ CI/CD Pipeline Implementation
✅ AWS Cloud Deployment
✅ Monitoring and Logging
✅ Nginx Configuration
✅ Infrastructure Automation

---

# ⚠️ Challenges Faced

🔐 SSH Key Authentication Issues
🌐 Dynamic Inventory Configuration
🛡️ Security Group Configuration
⚙️ Dependency Installation Errors

---

# 🔮 Future Enhancements

🚀 Kubernetes Integration
☁️ Terraform for Infrastructure as Code
🐳 Docker Containerization
📊 Advanced Monitoring Dashboards
🔄 Fully Automated CI/CD Pipeline

---

# 📸 Screenshots to Add

Add screenshots for:

📷 Ansible Playbook Execution
📷 AWS EC2 Instances
📷 Nginx Web Page
📷 Grafana Dashboard
📷 GitHub Actions Workflow

---

# 🏁 Conclusion

This project successfully demonstrates how DevOps tools like **Ansible** can automate configuration management and application deployment on AWS infrastructure.

The project:

✔️ Reduces manual effort
✔️ Improves deployment consistency
✔️ Follows modern DevOps best practices
✔️ Demonstrates Infrastructure Automation

---

# 👩‍💻 Author

## Dipali Nageshwar

### DevOps Internship Project

