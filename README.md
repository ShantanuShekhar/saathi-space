# 🏡 Saathi-Space
**Empowering societies to connect, manage, and thrive** – from residents to RWAs to guards, all in one place.

---

## 🌟 Overview

Saathi-Space is a modern, modular, and scalable Apartment Society Management Platform built with Java 17, Spring Boot, JWT-based authentication, and microservice-ready architecture.  
It empowers residents, guards, and RWAs to collaborate and manage daily society operations seamlessly.

---

## 🧩 Core Features

- 🔐 **Role-Based Access Control (RBAC)** with dynamic permissions
- 🧾 **Maintenance Billing & Invoicing**
- 🛠️ **Complaint & Issue Management**
- 🚪 **Visitor & Staff Entry Tracking**
- 📢 **Society Announcements & Voting**
- 📊 **Dashboard & Reports for Admins**
- 🌐 **API Gateway** integration for route-based security

---

## 🛠️ Tech Stack

- Java 17
- Spring Boot
- Spring Security + JWT
- MySQL / PostgreSQL
- Docker (Containerization)
- Kafka (Event-driven communication)
- Eureka (Service Discovery)
- Angular / React (Frontend - planned)
- Redis (Caching)

---

## 🏗️ Project Modules

| Module              | Description                                 |
|---------------------|---------------------------------------------|
| `auth-service`      | Handles authentication, RBAC, JWT issuing   |
| `gateway-service`   | API Gateway for routing based on roles      |
| `admin-service`     | Admin panel for RWA & society management    |
| `resident-service`  | Portal for residents                        |
| `guard-service`     | Visitor entry, alerts, and gate logs        |
| `billing-service`   | Generates bills, tracks payments            |

---

## 📦 Setup Instructions

### Prerequisites
- Java 17
- Docker & Docker Compose
- MySQL or PostgreSQL
- Maven 3+

### Run Locally

```bash
git clone https://github.com/yourusername/saathi-space.git
cd saathi-space
# Follow module README for each service

