# Database Design

## Overview

ISP Platform ERP uses PostgreSQL as its primary relational database management system.

The database has been designed using normalization principles while maintaining high performance for large-scale ISP operations.

The architecture supports a multi-tenant environment where multiple Internet Service Providers can operate securely within the same platform.

---

# Main Entities

## Companies

Stores ISP companies using the platform.

Responsibilities

- Company information
- Configuration
- Branding
- Localization

---

## Users

Platform administrators and operators.

Features

- Authentication
- Authorization
- RBAC
- Audit Trail

---

## Customers

Customer information.

Includes

- Personal information
- Contact information
- Billing information
- Status

---

## Services

Internet services assigned to customers.

Examples

- Residential Internet
- Business Internet
- Fiber
- Wireless
- Dedicated Links

---

## Plans

Internet plans.

Includes

- Name
- Speed
- Price
- PPPoE Profile
- Bandwidth

---

## Routers

MikroTik routers managed by the platform.

Stores

- IP Address
- API Port
- Credentials
- Status
- Location

---

## Invoices

Billing records.

Contains

- Invoice Number
- Amount
- Due Date
- Status

---

## Payments

Customer payments.

Supports

- Cash
- Bank Transfer
- Card
- Future Online Payments

---

## Tickets

Customer support tickets.

---

## Audit Logs

Platform activity logging.

---

# Relationships

Company

↓

Customers

↓

Services

↓

Plans

↓

Invoices

↓

Payments

---

# Future Enhancements

- Database Replication
- Automatic Backups
- Read Replicas
- High Availability
- Partitioning
