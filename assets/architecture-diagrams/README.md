# Architecture Diagrams (Visual)

These diagrams are sanitized and represent reusable SAP SD/OTC design patterns.

---

## 1) End-to-End OTC Architecture (SAP SD)

```mermaid
flowchart LR
  A[Customer / Channel] --> B[Inquiry / Quotation]
  B --> C[Sales Order]
  C --> D[Delivery]
  D --> E[Post Goods Issue]
  E --> F[Billing]
  F --> G[FI Accounting Document]

  C --- C1((Pricing))
  C --- C2((ATP))
  C --- C3((Credit Check))

  D --- D1((Shipping Point))
  D --- D2((Route))

  F --- F1((Output))
