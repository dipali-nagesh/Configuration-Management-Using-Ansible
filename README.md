# Configuration-Management-Using-Ansible

## Project Overview
This project demonstrates an end-to-end DevOps automation workflow using  Ansible on AWS. The main goal of this project is to server configuration, application deployment, and monitoring setup using  Configuration Management tools.

# Objectives
- Automate server configuration using Ansible
- Configure web servers using Nginx
- Implement monitoring using Prometheus and Grafana
- Reduce manual configuration effort
- Implement CI/CD pipeline integration
  
# Technologies Used
| Category | Tool |
|---|---|
| Cloud Platform | AWS EC2 |
| Configuration Management | Ansible |
| Web Server | Nginx |
| Monitoring | Prometheus, Grafana |
| Version Control | Git & GitHub |
| CI/CD | GitHub Actions / Jenkins |
| Operating System | Ubuntu Server |

# Architecture Diagram
Developer
   ↓
GitHub Repository
   ↓
CI/CD Pipeline
   ↓
AWS Infrastructure Provisioning
   ↓
Ansible Configuration Management
   ├── Install Packages
   ├── Configure Nginx
   ├── Deploy Application
   └── Configure Monitoring
   ↓
Prometheus + Grafana

# Project Workflow
## Step 1
Infrastructure

## Step 2 — Configuration Management
Ansible is used to:
- Install required packages
- Configure Nginx
- Configure monitoring tools
- 
### Ansible Commands

```bash
ansible all -m ping -i inventory.ini
ansible-playbook -i inventory.ini Configration.yml

## Step 4 — Monitoring Setup

Monitoring stack includes:
- Prometheus
- Grafana

Metrics are collected and visualized using Grafana dashboards.

# How to Run the Project

## Prerequisites
Install:
- Ansible
- Git
# Setup Instructions

## 1. Clone Repository

```bash
git clone https://github.com/dipali-nagesh/Configuration-Management-Using-Ansible.git

cd project-Configuration-Management-Using-Ansible

## 2. Configure AWS Credentials

```bash
aws configure

## 3. Provision Infrastructure
## 4. Configure Inventory File

Update EC2 IP addresses inside:

```text
inventory.ini
```
## 5. Run Ansible Playbooks

```bash
cd ansible

ansible-playbook -i inventory.ini Configration.yml

# CI/CD Pipeline

The CI/CD pipeline automates:
- Infrastructure provisioning
- Configuration management
- Application deployment

Tools used:
- GitHub Actions OR Jenkins

# Challenges Faced

- SSH key authentication issues
- Dynamic inventory configuration
- Security group configuration
# Learning Outcomes

Through this project, the following concepts were learned:


- Configuration Management
- Automation using Ansible
- CI/CD pipeline implementation
- Monitoring and logging
- Cloud deployment on AWS

# Future Enhancements

- Kubernetes integration
- Infrastructure as Code (IaC)-Terraform
- Dockers

# Screenshots

Add screenshots for:
- Ansible Playbook Execution
- EC2 Instances
- Nginx Web Page
- Grafana Dashboard

# Conclusion

This project successfully demonstrates how DevOps tools like Ansible can automate  configuration management. The project reduces manual effort, improves consistency, and follows modern DevOps best practices.

---

# Author

Dipali Nageshwar 
DevOps Internship Project



