# Static Website Deployment with Docker

📌 Project Overview

In this project, a simple static website (built with HTML and CSS) is packaged into a Docker container and served using a web server.

Docker ensures that the application runs the same way on amazon machine, solving the common issue of

🛠️ Tech Stack

- Docker
- HTML5
- CSS3
  
📂 Project Structure

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
