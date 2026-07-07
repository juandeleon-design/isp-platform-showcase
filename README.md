# 🚀 ISP Platform ERP

### Enterprise SaaS Platform for Internet Service Providers

![Status](https://img.shields.io/badge/Status-Active%20Development-success)
![License](https://img.shields.io/badge/License-Documentation%20Only-blue)
![Architecture](https://img.shields.io/badge/Architecture-Multi--Tenant-orange)
![Node.js](https://img.shields.io/badge/Backend-Node.js-green)
![React](https://img.shields.io/badge/Frontend-React-61DAFB)
![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-336791)

---

## 📌 Overview

ISP Platform ERP is an enterprise-grade SaaS platform developed to automate and centralize the daily operations of Internet Service Providers (ISPs).

The platform integrates customer management, billing, network automation, MikroTik RouterOS management, PPPoE synchronization, RADIUS authentication, reporting and financial administration into a single scalable solution.

This repository is a **technical showcase** intended for portfolio and recruitment purposes.

No proprietary production source code is included.

---

## 🌟 Key Features

- Multi-Tenant SaaS Architecture
- Customer Relationship Management (CRM)
- Billing & Invoicing
- Payment Management
- MikroTik Router Management
- PPPoE Profile Synchronization
- RADIUS Authentication
- Service Suspension Automation
- Automatic Cron Processing
- Multi Router Support
- Financial Reports
- Administrative Dashboard
- Role-Based Access Control (RBAC)
- RESTful API
- Audit Logs
- Email Notifications

---

## 🏗 Solution Architecture

```text
                        Internet

                           │

                   Cloudflare CDN

                           │

                    React Frontend

                           │

                     REST API (JWT)

                           │

                   Node.js + Express

                           │

                     PostgreSQL DB

            ┌──────────────┴──────────────┐

     MikroTik RouterOS             RADIUS Server

            │

     PPPoE Customers
```

---

## 💻 Technology Stack

### Frontend

- React
- TypeScript
- Vite
- Tailwind CSS

### Backend

- Node.js
- Express.js
- JWT Authentication
- REST APIs

### Database

- PostgreSQL

### Infrastructure

- Ubuntu Server
- Nginx
- Cloudflare
- GitHub

### Networking

- MikroTik RouterOS
- PPPoE
- RADIUS

---

## 📂 Documentation

- Architecture
- Modules
- Database Design
- REST API
- Deployment
- Security
- Roadmap

---

## 🎯 Current Status

✅ Active Development

Current focus:

- Multi Router Synchronization
- Payment Gateway Integration
- Cron Improvements
- Service Suspension Automation

---

## 🔒 Security

- JWT Authentication
- Role Based Access Control
- Password Hashing
- HTTPS
- Cloudflare Protection
- Audit Logging
- API Validation

---

## 👨‍💻 Lead Developer

Juan Antonio De León Godoy

Senior Full Stack Software Engineer

Software Architect

Telecommunications & Cloud Solutions Specialist

---

## 📄 License

This repository contains documentation only.

No production source code is distributed.
