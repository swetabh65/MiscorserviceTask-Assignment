# 🧱 Microservices-Based Node.js Application

This project is a **Dockerized Node.js microservices architecture** consisting of four independent services:

- 👤 `user-service`
- 📦 `product-service`
- 📑 `order-service`
- 🚪 `gateway-service` (acts as an API gateway)

Each service is containerized using **Docker** and orchestrated via **Docker Compose** for seamless development and deployment.

---

## 🛠️ Tech Stack

- **Node.js**
- **Express.js**
- **Docker**
- **Docker Compose**
- **WSL2 (Ubuntu on Windows)** (Optional for Windows users)

---

## 📁 Project Structure

Microservices-Task/
└── Microservices/
└── submission/
├── docker-compose.yml
├── user-service/
│ ├── Dockerfile
│ ├── app.js
│ └── package.json
├── product-service/
├── order-service/
└── gateway-service/


Each service contains:
- A `Dockerfile` for containerization
- A basic `Express.js` app exposing RESTful endpoints
- A health-check route: `/health`

---

## 🚀 Getting Started

### ✅ Prerequisites

- [Docker](https://docs.docker.com/get-docker/) installed and running
- Docker Compose (`docker compose` v2 CLI)
- (For Windows) Docker Desktop with **WSL2 integration enabled**

---

### 🔧 How to Run

![image](https://github.com/user-attachments/assets/60eaad02-1af3-472e-a136-d22d08266781)




From the root of the project (`submission/` folder):

```bash
# Build and run all services
docker compose up --build



---


### 🔧 How to Run




From the root of the project (`submission/` folder):


```bash
# Build and run all services
docker compose up --build


![image](https://github.com/user-attachments/assets/acfb04be-7457-4054-b471-b8887b026f97)

---

👨‍💻 Author
Swetabh Sonal
LinkedIn: linkedin.com/in/swetabhsonal
GitHub: github.com/swetabh65

