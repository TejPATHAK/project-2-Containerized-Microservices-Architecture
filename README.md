# 🚀 Project 2: Containerized Microservices Architecture

### 📖 Introduction

This project showcases a simple containerized architecture using a Python Flask web application and MongoDB, orchestrated with Docker Compose. It simulates a microservices environment suitable for learning containerization, inter-service communication, and environment-based configuration. The Flask app includes RESTful endpoints for logs, metrics, and health status, making it useful for DevOps and monitoring practice. MongoDB serves as the backend database, storing user input or test data.

The project is ideal for those beginning with Docker, Flask, and service orchestration principles in a DevOps context.


---

### 🔍 Project Overview

This project implements a **microservices-based architecture** where each service runs independently in its own container. It includes:

- ✅ A **Flask-based API service** for routing and response logic  
- ✅ A **Dockerfile** to containerize the Flask application  
- ✅ A **Docker Compose** setup to orchestrate containers  
- ✅ Endpoints for **health checks** (`/health`), **performance metrics** (`/metrics`), and **logging** (`/logs`)  
- ✅ A **unit test suite** (`test_app.py`) using Pytest  

---

### 🧰 Built With

- [Python (Flask)](https://flask.palletsprojects.com/)
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)
- [Pytest](https://docs.pytest.org/) – For testing


---

### 📦 Features

- **🧱 Containerized Architecture** – Entire app runs in isolated Docker containers for easier deployment and scalability.
- **⚡ Lightweight Flask App** – A fast and minimal API server ideal for microservice-based setups.
- **📡 Health Checks** – `/health` and `/metrics` endpoints help with service uptime monitoring and performance tracking.
- **📄 Logging Endpoint** – `/logs` provides access to application logs for debugging and observability.
- **🧪 Unit Testing Support** – Comes with `test_app.py` for verifying routes and application logic.
- **🔌 Port Configurable** – Easily modify exposed ports through `docker-compose.yml`.


---

## 🚀 Getting Started

### ✅ Prerequisites

Before running this project, ensure you have the following installed:

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/)
- Python 3+ (only if you want to run the Flask app locally)
- pip (Python package manager, for local development)


---
### 📂 Folder Structure

```bash
project-root/
│
├── app/                # Core Flask app logic
├── docker-compose.yml  # Docker Compose configuration
├── Dockerfile          # Dockerfile to containerize the app
├── requirements.txt    # Python dependencies
└── test_app.py         # Unit test file
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

## 📅 Project Status
✅ Stable
🛠️ Actively maintained
🔍 Open to contributions

## 👨‍💻 Author
- Tejaswi Pathak
- Connect on LinkedIn
