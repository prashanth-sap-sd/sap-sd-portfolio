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
flowchart TB
  P[Pricing Procedure] --> CT[Condition Types]
  CT --> AS[Access Sequences]
  AS --> T[Condition Tables]
  T --> CR[Condition Records]

  CT --- X1((Exclusion Groups))
  CT --- X2((Scales))
  CT --- X3((Manual Override Control))
  CR --- X4((Governance / Maintenance))
flowchart LR
  L[Legacy ECC Landscape] --> W[Fit-to-Standard Workshops]
  W --> S[Standardize OTC Design]
  S --> P[Simplify Pricing]
  P --> D[Reduce Custom Code]
  D --> M[Master Data Alignment]
  M --> G[S/4HANA Go-Live Readiness]

  D --- CC((Clean Core))
  M --- QA((Validation & Reconciliation))

4) Click **Commit changes**

✅ Now you have real “graphics” without creating any images.

---

## Step 3 — Update your main README to show these visuals
Open your repo **sap-sd-portfolio** → click **README.md** → click the pencil ✏️ (Edit)

Add this section near the top (right after your intro):

```md
---

## 🧩 Visual Architecture (Premium)

Open the diagrams here:
➡️ **[Architecture Diagrams](architecture-diagrams/README.md)**

---
