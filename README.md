# Static Website Deployment with Docker

#  Project Overview
This project demonstrates the deployment of a static website on a cloud server using AWS EC2, Nginx, and Docker.  
It covers the complete DevOps workflow including server setup, web hosting, containerization, and version control.

🛠️ Technologies Used
- ☁️ AWS EC2 (Cloud Server)
- 🌐 Nginx (Web Server)
- 🐳 Docker (Containerization)
- 🔁 Git & GitHub (Version Control)
- 💻 HTML & CSS (Frontend)

⚙️ Step-by-Step Implementation

🔹 Step 1: Launch EC2 Instance
- Created Ubuntu EC2 instance on AWS
- Configured Security Group:
  - Port 22 (SSH)
  - Port 80 (HTTP)
  - Port 8080 (Docker)

 🔹 Step 2: Connect to Server
Connected to EC2 using SSH (EC2 Instance Connect)

🔹 Step 3: Install Nginx

sudo apt update
sudo apt install nginx -y

🔹 Step 4: Deploy Website

index.html
style.css

🔹 Step 5: Host Website
