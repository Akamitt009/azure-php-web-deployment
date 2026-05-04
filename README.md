# 🚀 Azure PHP Web Deployment (Nginx + PHP-FPM)

## 📌 Project Overview
This project demonstrates the end-to-end deployment of a PHP-based web application on Microsoft Azure using a Linux Virtual Machine.

The deployment includes configuring Nginx as a web server, integrating PHP-FPM for dynamic content execution, and hosting a live production-ready website accessible via public IP.

---

## 🧰 Tech Stack
- Microsoft Azure (Virtual Machine)
- Ubuntu 24.04 (Linux)
- Nginx Web Server
- PHP 8.3 (PHP-FPM)
- SSH (Secure Remote Access)
- GitHub (Project Documentation)

---

## ⚙️ Deployment Steps
1. Provisioned Ubuntu Virtual Machine on Azure  
2. Connected to VM using SSH (key-based authentication)  
3. Installed Nginx web server  
4. Installed PHP (php-fpm, php-mysql)  
5. Configured Nginx for PHP processing (FastCGI)  
6. Uploaded website files to `/var/www/html`  
7. Set proper file permissions (`www-data`)  
8. Restarted services (Nginx & PHP-FPM)  
9. Debugged issues (403 Forbidden, 502 Bad Gateway)  

---

## 📂 Project Structure

deployment/
 ├── commands.md   # Deployment commands used
 ├── nginx.conf    # Nginx server configuration

---

## 🌐 Live Demo
👉 👉 [Live Website](http://4.213.35.81)
---

## 🔥 Key Learnings
- Azure VM provisioning and configuration  
- Linux server management (Ubuntu)  
- Nginx configuration and troubleshooting  
- PHP-FPM integration with Nginx  
- Handling real-world deployment errors (403, 502)  
- File permissions and web server debugging  

---

## 🚀 Highlights
- Deployed real-world PHP project on cloud infrastructure
- Successfully deployed a live PHP website on Azure  
- Configured production-like environment manually  
- Gained hands-on DevOps + Cloud experience  
- End-to-end troubleshooting and resolution  

---

## 👨‍💻 Author
**Amit Kumar**  
Cloud & DevOps Enthusiast  
