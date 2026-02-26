# AWS EC2 Launch and SSH Access Project

## 📌 Project Overview
This project demonstrates how to launch an AWS EC2 instance and securely connect to it using SSH. It covers instance configuration, key pair setup, and security group rules.

---
## Objective
- Launch a virtual server on AWS EC2
- Configure key pair and security group
- Connect to the instance using SSH

---

## Services Used
- AWS EC2
- AWS Security Groups
- SSH

---

## Steps Performed

### 1️⃣ Launch EC2 Instance
- Logged into AWS Console
- Navigated to EC2 Dashboard
- Clicked **Launch Instance**
- Selected AMI
- Selected instance type (t2.micro)

### 2️⃣ Configure Instance
- Created key pair
- Configured security group
  - Allowed SSH (Port 22)

### 3️⃣ Start Instance
- Launched instance successfully
- Copied public IP address

### 4️⃣ Connect via SSH
```bash
ssh -i key.pem ubuntu@public-ip
