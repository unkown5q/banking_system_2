
# 🏦 Banking Management System II

A full-stack banking web application that simulates real-world banking operations such as user onboarding, authentication, account management, and secure transactions.  
The project is Dockerized, cloud-deployed, and designed with production-style architecture.

---

## 🚀 Live Demo

🔗 **Production Deployment (Render):**  
https://your-project-name.onrender.com  
*(Replace with your actual Render URL if different)*

---

## 📌 Project Objective

To build a realistic banking system that demonstrates:

- Backend engineering with Django  
- Secure user authentication  
- Database design using PostgreSQL  
- Containerized deployment using Docker  
- Cloud hosting and CI/CD-style workflows  

This project reflects industry-level backend development practices.

---

## 🛠️ Tech Stack

### 🔧 Backend
- Python  
- Django  
- PostgreSQL (Neon Cloud Database)  

### 🎨 Frontend
- HTML  
- CSS  
- JavaScript  

### ☁️ DevOps & Deployment
- Docker  
- AWS EC2 (Infrastructure & Docker testing)  
- Render (Production hosting)  
- GitHub (Version control)  

---

## ✨ Key Features
- 🔐 User Registration & Authentication  
- 🧾 Bank Account Creation  
- 💰 Deposit & Withdrawal Operations  
- 🔁 Secure Transactions  
- 📊 Transaction History Tracking  
- 🐳 Fully Dockerized Application  
- 🌍 Cloud-Hosted with Public Access  

---

## 🧩 System Architecture

Local Development (VS Code)  
        ↓  
      GitHub  
        ↓  
```
┌───────────────────┐
│  Dockerized       │
│  Django App       │
└───────────────────┘
        ↓
 AWS EC2 (Infra & Testing)
        ↓
 Render (Production Hosting)
```

---

## 🐳 Docker Setup

The project is containerized using Docker to ensure:

- Environment consistency  
- Easy deployment across platforms  
- Dependency isolation  
- Production-like behavior  

**Build & Run (Local):**
```bash
docker build -t banking-system .
docker run -p 8000:8000 banking-system
```

---

## ☁️ AWS EC2 Usage

AWS EC2 was used to:

- Configure a Linux server  
- Deploy and test Docker containers  
- Manage ports and security groups  
- Gain hands-on experience with real backend infrastructure  

⚠️ EC2 instance was stopped after validation to avoid unnecessary costs.

---

## 🚀 Render Deployment

Render is used for final production hosting, providing:

- Free hosting tier  
- Automatic deployments from GitHub  
- HTTPS and public accessibility  
- Easy environment variable management  

---

## 🗂️ Database

- PostgreSQL hosted on Neon  
- Production-ready relational schema  
- Secure credential handling via environment variables  

---

## 🔐 Security Considerations

- Django authentication system  
- Hashed passwords  
- Environment variables for secrets  
- No hard-coded credentials  
```
