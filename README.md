# docker-nginx-static-site
# 🚀 Welcome to My Static Docker Website

This is a simple static website served using **Nginx** in a **Docker** container.

---

## 📖 Project Overview

This project demonstrates how to containerize and deploy a static website using Docker and Nginx. It serves a basic `index.html` page through an Nginx web server running inside a lightweight Docker container.

The `Dockerfile` uses the official `nginx:alpine` image and copies the static content into the default Nginx directory.

---

## 📁 Project Structure
docker-nginx-static-site/
├── Dockerfile
├── index.html
├── README.md
└── .gitignore

---

## 🐳 How to Run the Project

Make sure you have Docker installed, then run the following commands:

```bash
# Build the Docker image
docker build -t static-nginx .

# Run the container
docker run -d -p 8080:80 static-nginx
Now open your browser and go to:
👉 http://localhost:8080

🛠️ Key Concepts Covered

    Dockerfile basics

    Using official base images (nginx:alpine)

    Serving static HTML with Nginx

    Container build and run lifecycle

    Lightweight web hosting in containers      


