# REST API

## Overview

ISP Platform ERP exposes a RESTful API used by the frontend and external integrations.

Authentication is based on JSON Web Tokens (JWT).

---

# Authentication

POST

/api/auth/login

POST

/api/auth/logout

POST

/api/auth/refresh

---

# Customers

GET

/api/customers

POST

/api/customers

PUT

/api/customers/{id}

DELETE

/api/customers/{id}

---

# Services

GET

/api/services

POST

/api/services

---

# Plans

GET

/api/plans

POST

/api/plans

---

# Routers

GET

/api/routers

POST

/api/routers

---

# MikroTik

POST

/api/mikrotik/connect

POST

/api/mikrotik/sync

POST

/api/mikrotik/suspend

POST

/api/mikrotik/reconnect

---

# Billing

GET

/api/invoices

POST

/api/invoices

POST

/api/payments

---

# Reports

GET

/api/reports

---

# Security

JWT Authentication

HTTPS

Input Validation

Role Based Access Control
