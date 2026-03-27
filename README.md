# 🚀 AWS DevOps Automation Project

## 📌 Project Overview
This project demonstrates complete DevOps automation using:

- Terraform (Infrastructure as Code)
- Ansible (Configuration Management)
- AWS EC2 (Cloud Infrastructure)
- CloudWatch (Monitoring & Alerts)

---

## 🛠️ Technologies Used
- AWS EC2
- Terraform
- Ansible
- Nginx
- CloudWatch
- SNS (Email Alerts)

---

## ⚙️ What This Project Does

✔ Creates EC2 instance using Terraform  
✔ Configures server using Ansible  
✔ Installs and runs Nginx web server  
✔ Deploys a simple web page  
✔ Monitors CPU usage using CloudWatch  
✔ Sends email alert when CPU > 80%  
✔ Demonstrates backup/restore concept  

---

## 📂 Project Structure

---

## 🚀 Steps Performed

### 1. Infrastructure Setup (Terraform)
- Created EC2 instance
- Configured Security Group
- Added SSH Key Pair

---

### 2. Configuration Management (Ansible)
- Connected to EC2
- Installed Nginx
- Started and enabled service
- Created web page

---

### 3. Monitoring (CloudWatch)
- Created CPU utilization alarm
- Threshold set to 80%
- SNS email notification configured

---

### 4. Testing Alert
- Generated CPU load using:
- - Alarm triggered successfully
- Email notification received

---

### 5. Backup & Restore
- Created backup instance
- Verified website working on new instance

---

## 📸 Screenshots
### ⚙️ Terraform Apply (Step 1)
![Terraform Apply 1](screenshots/terraform-apply.png)

### ⚙️ Terraform Apply (Step 2)
![Terraform Apply 2](screenshots/terraform-apply-1.png)

### 🚀 EC2 Instance Before Terraform Apply
![Instance](screenshots/instance.png)

### 🚀 EC2 Instance After (Second View)
![Instance 2](screenshots/instance2.png)

### 📡 Public IP Check
![IP Check](screenshots/ip_check.png)

### 📂 Inventory File Configuration
![Inventory](screenshots/inventory-files.png)

### 🧪 CPU Stress Testing
![CPU Tester](screenshots/cpu-tester.png)

### 📊 CPU Usage Monitoring
![CPU Usage](screenshots/cpu-usage-.png)

### 🖼️ AMI Image Created
![AMI Image](screenshots/ami-image-created.png)

### 🔁 AMI Backup Created
![AMI Backup](screenshots/ami-backup.png)

### ▶️ Ansible Playbook
![Playbook](screenshots/playbook.png)

### ▶️ Ansible Playbook Execution
![Playbook Run](screenshots/playbook-run.png)

### 📩 SNS Email Notification
![SNS Mail](screenshots/sns-mail-.png)

### ✅ Final Verification
![Verified](screenshots/verified.png)

---

## 🎯 Outcome

This project demonstrates real-world DevOps workflow including:
- Infrastructure automation
- Server configuration
- Monitoring and alerting
- High availability concepts

---

## 👨‍💻 Author
Abhishek
