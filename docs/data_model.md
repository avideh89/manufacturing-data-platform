# Data Model

## Core Entities

- Customer
- Quotation
- Purchase Order
- Job
- Material
- Machine
- Production
- Delivery
- Invoice

---

## Relationships

Customer
    ↓
Quotation
    ↓
Purchase Order
    ↓
Job
    ↓
Production
    ↓
Delivery
    ↓
Invoice

Job
    ↓
Material

Production
    ↓
Machine

