# 🐳 Production-Ready Containerized Web Application

## 📦 Overview

This project demonstrates how to build and deploy a **production-ready containerized Python web application** using:

- **FastAPI** – modern, fast (high-performance) web framework for building APIs with Python.
- **PostgreSQL** – powerful, open-source object-relational database system.
- **Redis** – in-memory data structure store, used as a database, cache, and message broker.
- **Nginx** – reverse proxy server for load balancing, caching, and serving static files.
- **Docker Compose** – tool for defining and running multi-container Docker applications.

---

## 🚀 Getting Started

### Prerequisites

- Docker
- Docker Compose

### Running the Application

docker-compose up --build

📌 Architecture Overview [Nginx] --> [Uvicorn] --> [FastAPI App] --> [PostgreSQL + Redis]
![image](https://github.com/user-attachments/assets/6849badb-7e13-4b18-9ed9-eb83a9a5ac63)


