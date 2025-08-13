# Ansible-nginx-multi-server-deployments

# 📜 Project Description
This project demonstrates automated deployment of a static HTML website to multiple Ubuntu servers using Ansible. The process installs and configures Nginx as the web server and serves a responsive static page across all targeted servers.

The deployment is executed from a control node (Ansible master) and targets three remote Ubuntu servers simultaneously using SSH.

# 🚀 Project Highlights
Multi-server Deployment: Static website deployed to 3 servers at once

Automation with Ansible: No manual configuration, all done via playbook

Nginx Setup: Installs, enables, and starts Nginx automatically

Static HTML Page: Modern, responsive design served over HTTP

Infrastructure as Code (IaC): Fully repeatable process with version-controlled code

# 🛠 TECH STACK
HTML & CSS → Static Web Page

Ansible → Automation tool

Nginx → Web server

Ubuntu Linux → Server OS

SSH → Secure remote connection

# ⚙️ How It Works
Control Node Setup: Ansible is installed and configured on a master node.

Inventory & Playbook: Playbook specifies installation and deployment steps; inventory contains server details.

Run Playbook: ansible-playbook command triggers:

Install latest Nginx

Start and enable service

Copy HTML file to /var/www/html/index.html on each server

Result: Website is instantly live on all target servers.

# 📷 Live Example
After running the playbook, accessing any server's IP in a browser shows the deployed page:


(Example: http://35.154.96.145)

# 🎯 Resume-Ready Summary
Automated deployment of a responsive static website to multiple Ubuntu servers using Ansible and Nginx. Configured inventory for multi-server targeting and used SSH for secure communication. Demonstrated Infrastructure as Code principles and DevOps automation skills.

<img width="1911" height="957" alt="image" src="https://github.com/user-attachments/assets/aad21626-55f9-4363-98ed-78ceafd7df8a" />
