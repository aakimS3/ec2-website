# AWS EC2 Apache Website Project

## 🚀 Project Overview
This project demonstrates how to deploy a static website on an AWS EC2 instance using the Apache web server. The project includes Linux server configuration, web hosting, and Git/GitHub version control.

---

## 🧰 Technologies Used
- Amazon Web Services (EC2)
- Apache HTTP Server (httpd)
- Linux (Amazon Linux 2)
- Git & GitHub
- HTML5

---

## 📌 Project Steps

### 1. EC2 Setup
- Launched an EC2 instance using Amazon Linux 2
- Configured security group to allow HTTP (port 80) and SSH (port 22)

### 2. Apache Installation
```bash
sudo yum install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd
