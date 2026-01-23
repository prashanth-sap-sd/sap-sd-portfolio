# Architecture Diagrams (Visual)

These diagrams are sanitized reusable SAP SD design patterns.

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
flowchart TB
P[Pricing Procedure] --> CT[Condition Types]
CT --> AS[Access Sequences]
AS --> T[Condition Tables]
T --> CR[Condition Records]

CT --- E1((Exclusion Groups))
CT --- E2((Scales))
CT --- E3((Manual Controls))
CR --- E4((Governance))
flowchart LR
L[Legacy ECC] --> W[Fit-to-Standard Workshops]
W --> S[Standardize OTC]
S --> P[Simplify Pricing]
P --> D[Reduce Custom Code]
D --> M[Master Data Alignment]
M --> G[Go-Live Readiness]

D --- C((Clean Core))
M --- V((Validation))
