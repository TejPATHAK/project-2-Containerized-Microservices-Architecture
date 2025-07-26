# 🚀 Project 2: Containerized Microservices Architecture

A complete DevOps-ready microservices application leveraging **Docker**, **Flask**, **MongoDB**, **Nginx**, and **CI/CD pipelines**. Designed for scalability, observability, and performance — deploy your apps faster and smarter.

---

## 🔍 Project Overview

This project implements a **microservices-based architecture** where each service runs independently in its own container. It includes:

- A Flask-based web frontend
- A MongoDB database service
- Docker Compose orchestration
- Health check and logging endpoints
- Scalable Nginx reverse proxy
- CI/CD integrations possible via Jenkins or GitHub Actions

---

## 🧰 Built With

- Python (Flask)
- MongoDB
- Nginx
- Docker & Docker Compose
- GitHub Actions / Jenkins (for CI/CD)

---

## 📦 Features

- 🧱 **Microservice Isolation** — Each service runs in its own container.
- 🔁 **Docker Compose** — Simplifies orchestration of services.
- 📡 **Health Monitoring** — `/health` endpoint available.
- 📊 **Logging & Metrics** — Access `/logs` and `/metrics` endpoints.
- 🐳 **Containerization** — Easy to deploy and scale.
- ⚙️ **Reverse Proxy** — Handled via Nginx.

---

## 🚀 Getting Started

### ✅ Prerequisites

- Docker & Docker Compose installed
- Python 3+ and pip (optional for local run)

---
###📂 Folder Structure

```bash
project-root/
│
├── app/                # Flask app logic
├── nginx/              # Nginx reverse proxy config
├── docker-compose.yml
├── Dockerfile
├── requirements.txt
└── test_app.py
```

### 📁 Clone the Repository

```bash
git clone https://github.com/TejPATHAK/project-2-Containerized-Microservices-Architecture.git
cd project-2-Containerized-Microservices-Architecture
```
## ⚙️ Run the App with Docker Compose

```bash
docker-compose up --build
```
🔗 Access the app at: http://localhost:80

## 👨‍💻 Author
Tejaswi Pathak
Connect on LinkedIn

## 📅 Project Status
✅ Stable
🛠️ Actively maintained
🔍 Open to contributions
