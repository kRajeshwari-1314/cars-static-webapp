# cars-static-webapp
Dockerized static website showcasing top car brands, built with HTML, CSS and deployed with NGINX on AWS EC2

# 🚗 Cars Static WebApp — Dockerized with NGINX

A modern static website showcasing luxury car brands, built with **HTML** and **CSS**, and deployed inside a **Docker container powered by NGINX** for high-performance web serving.  
This project demonstrates end-to-end DevOps workflow — from containerization to deployment on **AWS EC2 Linux**.

---

## 🧩 Features
- Responsive static front-end using HTML5 & CSS3  
- Dockerized setup for consistent deployment  
- NGINX as the web server for optimized delivery  
- Simple and fast deployment on AWS EC2  

---

## 🛠️ Tech Stack
**HTML5** | **CSS3** | **Docker** | **NGINX** | **AWS EC2 (Linux)**

---

## ⚙️ How to Run Locally
```bash
# Clone this repository
git clone https://github.com/<your-username>/cars-static-webapp.git
cd cars-static-webapp

# Build Docker image
docker build -t cars-static-webapp .

# Run the container
docker run -d -p 8080:80 cars-static-webapp

