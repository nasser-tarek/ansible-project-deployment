## 📦 Ansible Role-Based Deployment

This repository contains an Ansible project designed to automate the deployment of a simple web application stack.  
It follows best practices by organizing tasks into reusable **roles** and managing secrets securely with **Ansible Vault**.

### Features
- 🚀 Automated installation and configuration of **Nginx** web server.
- 🛢️ Deployment of **MySQL** database with user and schema creation.
- 🔑 Secure password and secret management with **Ansible Vault**.
- ⚡ Role-based structure for reusability and scalability.
- 📂 Centralized inventory and configuration management.

### Project Structure
- `roles/nginx_app/` → Installs and configures Nginx.
- `roles/db/` → Installs MySQL, creates database, users, and sets root password.
- `group_vars/` → Centralized variables for environment configuration.
- `ansible.cfg` → Project configuration file.
- `inventory.ini` → Inventory file for target hosts.

### Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
