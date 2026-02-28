# Ansible Playbook: Install and Manage Nginx on Ubuntu

## 📌 Project Overview

This project demonstrates how to automate the installation and management of Nginx on an Ubuntu target machine using Ansible.

The playbook performs the following tasks:

- Updates apt package cache
- Installs Nginx
- Starts and enables Nginx service
- Checks installed Nginx version
- Verifies Nginx service status
- Stores execution logs in output.log

---

## 🛠 Technologies Used

- Ansible
- Ubuntu Linux EC2 instance
- Nginx
- SSH
- YAML

---
## 📂 Project Structure
├── install_manage_nginx.yml
├── inventory
├── output.log
└── README.md

### 1️⃣ Clone the Repository
git clone https://github.com/vanshikajaiswal814/Ansible-nginx-setup.git


### 2️⃣ Update Inventory File

Edit the inventory file with your target Ubuntu server IP:

### 3️⃣ Run the Playbook and store the execution logs in output.log file
ansible playbook -i inventory install_manage_nginx.yml | tee output.log

## ✅ Playbook Workflow

1. Updates Ubuntu package cache
2. Installs Nginx using apt module
3. Starts and enables Nginx service
4. Checks Nginx version (`nginx -v`)
5. Validates Nginx service status

   ## 👩‍💻 Author
Vanshika Jaiswal
