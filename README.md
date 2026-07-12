<p align="center">
  <img src="assets/banner.png" alt="ISP Platform ERP Banner" width="100%">
</p>

<h1 align="center">🚀 ISP Platform ERP</h1>

<p align="center">
Enterprise Multi-Tenant SaaS Platform for Internet Service Providers
</p>

<p align="center">

![Status](https://img.shields.io/badge/Status-Active%20Development-success)
![Version](https://img.shields.io/badge/Version-v1.0-blue)
![Architecture](https://img.shields.io/badge/Architecture-Multi--Tenant-orange)
![Node.js](https://img.shields.io/badge/Backend-Node.js-339933?logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/Frontend-React-61DAFB?logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-Ubuntu-E95420?logo=ubuntu&logoColor=white)
![MikroTik](https://img.shields.io/badge/MikroTik-RouterOS-blue)

</p>

---

# 📑 Table of Contents

- [📖 Overview](#-overview)
- [🎯 Business Goals](#-business-goals)
- [🌟 Key Features](#-key-features)
- [🏗 Solution Architecture](#-solution-architecture)
- [📚 Technical Documentation](#-technical-documentation)
- [📐 Engineering Diagrams](#-engineering-diagrams)
- [💻 Technology Stack](#-technology-stack)
- [🔒 Security](#-security)
- [🚀 Current Status](#-current-status)
- [👨‍💻 Lead Developer](#-lead-developer)

---

# 📖 Overview

ISP Platform ERP is an enterprise-grade multi-tenant SaaS platform developed to automate and centralize the daily operations of Internet Service Providers (ISPs).

The platform integrates billing, CRM, MikroTik RouterOS management, PPPoE provisioning, RADIUS authentication, customer management, reporting and financial administration into a single cloud-ready solution.

> **This repository contains documentation only.**
>
> Production source code is private and intentionally excluded.

---

# 🎯 Business Goals

- Automate ISP operations
- Centralize customer management
- Simplify billing and invoicing
- Integrate MikroTik RouterOS
- Manage PPPoE services
- Support multiple routers
- Generate operational reports
- Provide a scalable SaaS platform

---

# 🌟 Key Features

- Multi-Tenant SaaS
- Customer Management (CRM)
- Billing & Invoicing
- Payment Management
- MikroTik Router Integration
- PPPoE Synchronization
- RADIUS Authentication
- Service Suspension Automation
- REST API
- Audit Logs
- Role-Based Access Control (RBAC)
- Administrative Dashboard

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
                  Node.js + Express.js
                            │
                       PostgreSQL
            ┌──────────────┴──────────────┐
      MikroTik RouterOS            RADIUS Server
            │
      PPPoE Customers
```

---

# 📚 Technical Documentation

| Document | Description |
|-----------|-------------|
| 📐 Architecture | Overall platform architecture |
| 📦 Modules | Business modules |
| 🗄 Database | Entity relationship model |
| 🔌 REST API | API endpoints |
| 🔒 Security | Authentication & Authorization |
| 🚀 Deployment | Production deployment |
| 🛣 Roadmap | Future development |
| 📊 Diagrams | Technical architecture diagrams |

---

# 📐 Engineering Diagrams

The following diagrams describe the internal architecture and engineering design of ISP Platform ERP.

---

### 🏗 System Architecture

[![System Architecture](diagrams/01-system-architecture.png)](diagrams/01-system-architecture.png)

High-level platform architecture.

---

### 🗄 Database ER Diagram

[![Database ER Diagram](diagrams/02-database-er-diagram.png)](diagrams/02-database-er-diagram.png)

Main entities and relationships.

---

### 💳 Billing Flow

[![Billing Flow](diagrams/03-billing-flow.png)](diagrams/03-billing-flow.png)

Invoice generation and payment workflow.

---

### 👤 Customer Lifecycle

[![Customer Lifecycle](diagrams/04-customer-lifecycle.png)](diagrams/04-customer-lifecycle.png)

Customer onboarding and service lifecycle.

---

### 🌐 MikroTik Integration

[![MikroTik Integration](diagrams/05-mikrotik-integration.png)](diagrams/05-mikrotik-integration.png)

Communication with MikroTik RouterOS.

---

### 🔌 PPPoE Provisioning

[![PPPoE Provisioning](diagrams/06-pppoe-provisioning.png)](diagrams/06-pppoe-provisioning.png)

Automatic provisioning process.

---

### 🔐 Authentication Flow

[![Authentication Flow](diagrams/07-authentication-flow.png)](diagrams/07-authentication-flow.png)

JWT Authentication and RBAC.

---

### ⏰ Cron Job Workflow

[![Cron Job Workflow](diagrams/08-cron-job-workflow.png)](diagrams/08-cron-job-workflow.png)

Scheduled background services.

---
