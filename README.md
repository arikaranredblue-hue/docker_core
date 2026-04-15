# 🚀 Static Website Deployment using Node.js + Nginx + Docker

## 📌 Project Overview
This project is a simple **static website deployment** using:
- Node.js (for project structure / build handling)
- Nginx (for serving static content)
- Docker (for containerization)
- Custom Nginx configuration
- Custom Nginx user for security

---

## 🛠️ Tech Stack
- HTML, CSS, JavaScript
- Node.js
- Nginx
- Docker

---

## 📁 Project Structure

📦 DOCKER_1
 ┣ 📂 .github
 ┃ ┗ 📂 workflows
 ┃   ┗ 📄 deploy.yaml
 ┃
 ┣ 📂 frontend
 ┃ ┣ 🐳 Dockerfile
 ┃ ┣ ⚙️ nginx.conf
 ┃ ┣ 🌐 index.html
 ┃ ┣ 🎨 style.css
 ┃ ┗ ⚡ script.js
 ┃
 ┣ 🚫 .gitignore
 ┣ 📘 README.md
 
 
---

## 🐳 Docker Setup

### 🔨 Build Docker Image
```bash
docker build -t static-nginx-app .

### 🔨 Create ec2 and pull the image manually and run

********   Refer the AWS Pdf ***********