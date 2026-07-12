# 🚀 ISP Platform ERP

<h3 align="center">
Enterprise Multi-Tenant SaaS Platform for Internet Service Providers
</h3>

<p align="center">

![Status](https://img.shields.io/badge/Status-Active%20Development-success)
![Architecture](https://img.shields.io/badge/Architecture-Multi--Tenant-orange)
![Node.js](https://img.shields.io/badge/Backend-Node.js-339933?logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/Frontend-React-61DAFB?logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-Ubuntu-E95420?logo=ubuntu&logoColor=white)
![MikroTik](https://img.shields.io/badge/MikroTik-RouterOS-blue)

</p>

---

# 📖 Overview

ISP Platform ERP is an enterprise-grade SaaS platform designed to automate every critical operation of an Internet Service Provider.

The platform centralizes customer management, automated billing, MikroTik RouterOS integration, PPPoE provisioning, RADIUS authentication, financial administration and reporting into a single cloud-ready solution.

> **This repository is a public technical showcase intended for portfolio and recruitment purposes.**
>
> Production source code remains private.

---

# 🎯 Business Goals

✔ Customer Management

✔ Automated Billing

✔ Payment Management

✔ MikroTik Integration

✔ PPPoE Automation

✔ RADIUS Authentication

✔ Multi Router Support

✔ Service Suspension Automation

✔ Financial Reports

✔ Dashboard & Analytics

✔ Multi-Tenant Architecture

✔ REST API

---

# 🏗 Solution Architecture

```text
                          Internet

                               │

                        Cloudflare CDN

                               │

                     React + TypeScript

                               │

                        REST API (JWT)

                               │

                    Node.js / Express.js

                               │

                         PostgreSQL

               ┌──────────────┴──────────────┐

        MikroTik API                 RADIUS Server

               │

        PPPoE Customers
```

---

# 📐 Technical Documentation

| Documentation | Description |
|---------------|-------------|
| 📐 Architecture | Overall system architecture |
| 📦 Modules | Functional modules |
| 🗄 Database | Entity Relationship Model |
| 🔌 REST API | REST endpoints |
| 🔒 Security | Authentication & RBAC |
| 🚀 Deployment | Production deployment |
| 🛣 Roadmap | Future development |
| 📊 Technical Diagrams | Engineering diagrams |

---

# 🖼 Architecture & Engineering Diagrams

## 1️⃣ System Architecture

Complete high-level architecture of the platform.

![System Architecture](images/01-system-architecture.png)

---

## 2️⃣ Database ER Diagram

Database entities and relationships.

![Database ER Diagram](images/02-database-er-diagram.png)

---

## 3️⃣ Billing Flow

Invoice generation, payment processing and service suspension workflow.

![Billing Flow](images/03-billing-flow.png)

---

## 4️⃣ Customer Lifecycle

Customer onboarding, activation, billing and support lifecycle.

![Customer Lifecycle](images/04-customer-lifecycle.png)

---

## 5️⃣ MikroTik Integration

Communication between ERP and RouterOS API.

![MikroTik Integration](images/05-mikrotik-integration.png)

---

## 6️⃣ PPPoE Provisioning

Automatic provisioning workflow.

![PPPoE Provisioning](images/06-pppoe-provisioning.png)

---

## 7️⃣ Authentication Flow

JWT Authentication and RBAC.

![Authentication Flow](images/07-authentication-flow.png)

---

## 8️⃣ Cron Job Workflow

Scheduled background processes.

![Cron Job Workflow](images/08-cron-job-workflow.png)

---

# 💻 Technology Stack

## Frontend

- React
- TypeScript
- Vite
- Tailwind CSS

## Backend

- Node.js
- Express.js
- REST API
- JWT

## Database

- PostgreSQL

## Infrastructure

- Ubuntu Server
- Nginx
- Cloudflare
- GitHub

## Networking

- MikroTik RouterOS
- PPPoE
- RADIUS

---

# 🔐 Security

- JWT Authentication
- Role Based Access Control (RBAC)
- Password Hashing
- HTTPS / SSL
- Cloudflare WAF
- API Validation
- Audit Logs
- Secure Sessions

---

# 🚀 Current Development

## Completed

- Customer Management
- Billing
- Plans
- Services
- Dashboard
- Router Management
- Authentication
- Reporting

---

## In Progress

- Multi Router Synchronization
- PPPoE Synchronization
- Payment Gateway
- Billing Automation
- Cron Improvements

---

## Planned

- Docker Deployment
- Kubernetes
- Customer Portal
- WhatsApp Notifications
- Mobile Application
- IPv6 Native Support
- Monitoring Dashboard

---

# 👨‍💻 Lead Developer

## Juan Antonio De León Godoy

Senior Full Stack Software Engineer

Software Architect

Telecommunications & Cloud Solutions Specialist

📍 Pachuca, Hidalgo, México

🌎 Open to Remote Opportunities

---

# 📄 Repository Notice

This repository contains documentation only.

The production source code is proprietary and intentionally excluded.

Its purpose is to demonstrate the project's architecture, engineering approach and technical capabilities.

---

# ⭐ Project Status

Active Development

Enterprise SaaS

Multi-Tenant

Cloud Ready

Designed for Scalability
