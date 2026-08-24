# 📚 Bookstore Microservices

A full-stack **microservices-based bookstore application** built to explore scalable web application architecture, service-to-service communication, and modern software development practices.

## ✨ Overview

The application is composed of a React frontend and independent Node.js services for:

- 📖 Book catalog and inventory
- 🛒 Order management
- 💳 Payment processing
- 🗄️ Service-specific PostgreSQL databases

## 🧱 Architecture

```text
                    ┌─────────────────┐
                    │  React Frontend  │
                    └────────┬────────┘
                             │
                    ┌────────▼────────┐
                    │   API Gateway   │
                    └───────┬─────────┘
                            │
          ┌─────────────────┼─────────────────┐
          ▼                 ▼                 ▼
   Catalog Service    Orders Service    Payments Service
          │                 │                 │
          ▼                 ▼                 ▼
      PostgreSQL        PostgreSQL        PostgreSQL
```

## 🛠️ Technologies

**Frontend**  
React · HTML · CSS

**Backend**  
Node.js · REST APIs · Microservices

**Data**  
PostgreSQL

**Application Runtime**  
Docker · Docker Compose

**Cloud**  
AWS

## 🚀 Local Development

```bash
git clone https://github.com/saikrishna-bethamcharla/Bookstore-microservices.git
cd Bookstore-microservices
docker-compose up --build
```

Open the frontend at `http://localhost:3000`.

## 🎯 What This Project Demonstrates

- Designing independent backend services
- Building REST APIs
- Connecting frontend and backend systems
- Service-specific data models
- Containerized local development
- Structuring a production-oriented full-stack application

## 👤 Author

**Sai Krishna Bethamcharla**

AI & Software Developer · AI Video Creator · Creative Technologist
