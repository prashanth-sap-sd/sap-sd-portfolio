# Case Study 3: SAP S/4HANA Full Lifecycle Implementation — Molina Healthcare

> **Client:** Molina Healthcare  
> **Role:** SAP OTC Lead Consultant  
> **Duration:** January 2020 — April 2021 (16 months)  
> **Programme Type:** Full Lifecycle SAP S/4HANA Implementation (Agile delivery)  
> **Environment:** SAP ECC 6.0 · S/4HANA · SD · MM · WM · FI/CO · EDI/IDoc  

---

## Executive Summary

Acted as OTC Lead Consultant on Molina Healthcare's full lifecycle SAP S/4HANA implementation — delivered using Agile methodology across a 16-month engagement. Accountable for blueprinting, end-to-end OTC configuration, testing cycles, defect triage, training, and hypercare. Led onsite and offshore teams through design, configuration, and UAT across multiple SD/OTC workstreams.

Molina Healthcare is one of the largest US managed care organisations — serving millions of Medicaid and Medicare members across 18 states. Their SAP implementation required healthcare-specific OTC processes including complex contract management, pricing validation for regulated services, and high-volume billing with strict compliance requirements.

> *"In healthcare, billing accuracy is not just a business requirement — it's a compliance requirement. Every pricing and billing scenario had to be tested to zero tolerance."*

---

## Client Background

Molina Healthcare provides government-sponsored managed care services across Medicaid, Medicare, and Marketplace segments. Their SAP OTC landscape covers:
- Contract-based service billing with complex pricing for regulated healthcare services
- High-volume order and billing processing across 18 state operations
- Strict revenue recognition and compliance requirements
- Deep integration between SD, FI/CO, MM for end-to-end financial accuracy

---

## My Role: OTC Lead Consultant

As OTC Lead, I was accountable for the full SD workstream — not just configuration but team leadership, governance, and delivery outcomes:
- Managed blueprinting through go-live across all OTC workstreams
- Guided onsite and offshore teams through design, configuration, and UAT
- Prepared functional specs for RICEFW objects and oversaw development, testing, deployment
- Led UAT cycles and hypercare — the last person accountable for OTC quality at go-live

---

## Phase-by-Phase Delivery

### Blueprint & Design (Months 1–4)

**Agile Blueprint Approach**
Rather than a traditional monolithic blueprint, we ran sprint-based design sessions — each sprint covering a specific OTC process area and producing a signed design document within 2 weeks.

**Process Areas Blueprinted:**
- Order Management: standard, rush, cash sales, make-to-order, third-party, cross-company
- Pricing: procedure design, condition types, contract pricing, credit/debit note handling
- Contract Management: service contracts, quantity/value contracts, renewal processing
- Billing: standard billing, periodic billing, milestone billing, credit/debit memos, output
- Logistics Execution: delivery, shipping, route determination, WM integration
- Credit Management: risk categories, credit groups, automated credit check rules
- Integration: SD-FI account determination, SD-MM ATP, SD-WM warehouse processing

### Configuration (Months 3–10)

**Order Management**
- Customised IMG settings for the full document landscape: quotations, inquiries, sales orders (standard, rush, cash), inbound/outbound deliveries, billing, and returns
- Configured OTC scenarios: cash sales, make-to-order, follow-up orders, automatic partner determination
- Defined sales document types, number ranges, item category groups, and item categories

**Pricing Architecture**
- Developed complex pricing procedures tailored to Molina's regulated pricing model
- Full condition technique setup: condition types, access sequences, condition tables, condition records
- Configured special condition types for healthcare service pricing
- Implemented free goods determination and credit/debit note procedures
- Configured condition exclusion groups to prevent incorrect discount stacking
- Maintained condition records for consistent pricing across all 18 state operations

**Contract & Billing Configuration**
- Configured listing and exclusion logic, material determination, copy controls, delivery types
- Set up comprehensive billing: billing document types, invoice lists, billing plans (periodic and milestone), copy controls for sales documents
- Configured output determination procedures for all billing document types
- Managed credit memo and debit memo processing aligned to healthcare contract adjustment requirements

**Logistics Execution**
- Configured full logistics execution: inbound and outbound deliveries, shipping types, transportation zones, transportation groups, route determination
- Managed route determination including modes of transport and shipping points
- Executed stock placements and removals using WM put-away and picking strategies

**EDI & Integration**
- Configured ALE configuration: partner profiles, segments, IDoc interface creation and extension
- Integrated EDI with non-SAP applications using standard X12 and EDIFACT formats
- Integrated MM for availability check using ATP logic

**Credit Management**
- Set up credit management: risk categories, credit groups, automated credit checks
- Configured transfer of requirements (TOR) and participated in credit management configurations

### RICEFW Delivery

Prepared functional specifications for RICEFW objects across the OTC workstream:
- Oversaw development, testing, and deployment of enhancements in pricing and billing
- Coordinated with ABAP team on pricing routines, custom output forms, and billing enhancements
- All RICEFW items delivered through Agile sprint cycles with formal sign-off before transport

### Testing (Months 8–13)

**SIT Execution**
- Performed unit and integration testing across SAP SD/MM/WM processes
- Ensured complete coverage and business alignment for all configured scenarios
- Managed defect log: classified, triaged, and tracked all defects to resolution

**UAT Leadership**
- Led UAT cycles for OTC scenarios including:
  - Complex pricing validation across all contract types
  - Contract renewal and re-pricing scenarios
  - Billing outputs for all billing document types
  - Credit/debit adjustments and memo processing
- Managed UAT defect triage — distinguishing configuration issues from training gaps from data issues
- Achieved UAT sign-off within planned cycle timelines

### Hypercare & AMS Support (Months 14–16)

**Hypercare Structure**
- On-call OTC lead throughout 6-week hypercare period
- Daily stand-up: incident review, priority actions, cross-functional coordination
- P1/P2 SLA adherence — all critical issues resolved within target windows

**Issue Categories Resolved in Hypercare:**
- Pricing discrepancies: condition record gaps for specific contract types
- Contract errors: copy control issues affecting contract renewal pricing
- Billing failures: output determination gaps for specific billing scenarios
- Integration defects: SD-FI account determination for new GL combinations

**AMS Transition**
- Transitioned to Application Management Support (AMS) model at end of hypercare
- Produced full knowledge transfer documentation for AMS team
- Delivered Top 10 Issues Guide for production support team

---

## Team Leadership

As OTC Lead, I managed a team spanning onsite and offshore:

| Role | Location | Scope |
|---|---|---|
| OTC Lead (myself) | Onsite | Full workstream ownership, client relationship |
| SD Configurator | Offshore | Configuration execution, unit testing |
| Test Analyst | Offshore | SIT script execution, defect logging |
| Business Analyst | Onsite | Workshop facilitation, documentation |

**Offshore coordination approach:**
- Daily 30-minute sync call with offshore team (overlap window)
- All design decisions documented in Confluence before offshore build starts
- Transport review: every transport peer-reviewed before promotion to QA
- Weekly defect triage call including offshore team

---

## Key Deliverables

| Deliverable | Description |
|---|---|
| Agile Blueprint Documents | Sprint-based design docs per process area |
| RICEFW Functional Specs | Complete functional specifications for all enhancements |
| OTC Configuration | Full ECC/S4 OTC landscape configuration |
| Pricing Procedure Design | Complex condition technique for healthcare pricing |
| ALE/EDI Configuration | Partner profiles, IDoc interfaces, X12/EDIFACT |
| SIT Test Pack | Full integration test coverage |
| UAT Test Pack & Sign-off | Business user acceptance documentation |
| Hypercare Tracker | 6-week incident log and resolution documentation |
| AMS Knowledge Transfer | Production support handover documentation |
| Top 10 Issues Guide | Self-service diagnostic guide for support team |

---

## Technical Environment

```
SAP Platform:    S/4HANA (Full Lifecycle Implementation)
Modules:         SD · MM · WM · FI/CO
EDI:             X12 · EDIFACT · IDocs · ALE
Tools:           Solution Manager · Remedy · HPQC · ServiceNow
Methodology:     Agile · SAP Activate · ITIL
```

---

## Key Achievements

- ✅ Full lifecycle implementation delivered on time across 16 months
- ✅ OTC workstream led end-to-end: blueprint → configuration → testing → go-live → hypercare
- ✅ Managed onsite + offshore team through complete delivery cycle
- ✅ Complex healthcare pricing model configured with zero tolerance for billing errors
- ✅ ALE/EDI integration delivered for all key trading partners
- ✅ AMS transition completed with full knowledge transfer

---

## What Made This Engagement Distinctive

**Healthcare pricing complexity:**
Molina's pricing is governed by state contract regulations — not just commercial business rules. This means pricing errors are a compliance risk, not just a financial one. The pricing design and testing approach had to be more rigorous than a standard commercial implementation — every condition type, every access sequence priority, and every exclusion group logic was tested to zero tolerance.

**Agile delivery for a complex SAP implementation:**
Running SAP SD implementation in Agile sprints requires a different mindset. Rather than waiting for a complete blueprint before building, each sprint produced working configuration from a signed design — this surfaced integration issues earlier and allowed the business to see working processes sooner. The key discipline was ensuring design sign-off happened within the sprint before build started.

**Offshore team leadership on a critical workstream:**
As OTC Lead managing offshore configuration, the key discipline was documentation quality. Every design decision had to be written clearly enough that an offshore configurator could implement it correctly without a 30-minute call to clarify. This forced a documentation standard that ultimately produced better handover material at the end of the project.

---

> *Client name used with professional discretion. All configuration values, system landscape specifics, and business process details reflect the nature and scope of the engagement.*
