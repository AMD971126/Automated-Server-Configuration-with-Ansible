# Automated Server Configuration with Ansible
This repository contains an **Ansible project** that automates full Linux server provisioning and configuration.
---

## 📌 Project Overview
This project demonstrates how to automate Linux server provisioning and configuration using **Ansible**.  
The playbook covers key system administration tasks such as installing web servers, managing configuration files, gathering system facts, installing multiple packages, and monitoring uptime.

---

## 🚀 Features
- **Conditional Web Server Deployment**  
  - Installs `apache2` on Debian systems or `httpd` on RedHat systems.  
  - Includes memory checks (≥ 512MB) to ensure system readiness.  

- **Configuration Management**  
  - Creates a directory `/etc/demo_config`.  
  - Generates a configuration file with a custom message.  

- **System Facts Gathering**  
  - Prints number of CPU cores.  
  - Prints total memory (in MB).  

- **Package Management**  
  - Installs multiple packages (`curl`, `htop`, `git`) using a loop.  

- **System Monitoring**  
  - Runs the `uptime` command and displays system uptime.  

---

## 🛠️ Tools & Technologies
- Ansible  
- YAML  
- Linux (Debian/RedHat)  

---

## 📂 Project Structure
```
.
├── playbook.yml      # Main Ansible playbook
├── inventory         # Inventory file (not included here, adjust as needed)
└── README.md         # Project documentation
```

---

## 🎯 Outcome
- Automated Linux server provisioning and setup.  
- Reduced manual work by automating repetitive tasks.  
- Achieved consistent and reliable server configurations across environments.  

---

## 👤 Author
**Ahmed Mohamed Daoud**  
- IT Specialist | Network Engineer | DevOps Enthusiast  
- [LinkedIn](https://www.linkedin.com/in/ahmedmohameddaoud/) | [GitHub](https://github.com/AMD971126)  
