# Case Study 1: SAP ECC to S/4HANA Migration — Experian

> **Client:** Experian (Costa Mesa, CA, USA) — Global Information Services  
> **Role:** SAP SD / S/4HANA Consultant  
> **Duration:** August 2023 — Present  
> **Programme Type:** Full Lifecycle ECC 6.0 → S/4HANA Migration  
> **Environment:** SAP ECC 6.0 · SAP S/4HANA · FI · CO · SD · MM · WM · ALE/EDI  

---

## Executive Summary

Led the SAP SD workstream on Experian's full lifecycle migration from SAP ECC 6.0 to S/4HANA — one of the most complex SAP transformations in the financial information services sector. Accountable for end-to-end OTC process design, pricing architecture, billing configuration, logistics execution, output management migration, and post-go-live hypercare stabilisation.

Experian operates a highly complex SD landscape involving contract-based service billing, advanced ATP, intercompany processes, and deep EDI/IDoc integration with external partners. The migration required not just a technical lift-and-shift but a fundamental redesign of several SD processes to align with S/4HANA best practices and clean-core principles.

> *"This was not a simple upgrade. Experian's SD landscape carried years of customisation debt — our job was to migrate the business value while eliminating the technical debt."*

---

## Client Background

Experian is one of the world's leading global information services companies — operating across credit services, data analytics, and consumer information. Their SAP landscape supports complex Order-to-Cash processes including:
- Contract-based service agreements with milestone and recurring billing
- High-volume transaction processing across multiple sales organisations
- Deep integration with FI-AR for revenue recognition and credit management
- EDI connectivity with major financial institution partners

---

## My Scope & Responsibilities

### OTC Process Design & Configuration
- Led full OTC process design across the S/4HANA environment — from inquiry and quotation through sales order, delivery, billing, and FI posting
- Customised all IMG settings for the complete document landscape: quotations, inquiries, standard orders, rush orders, cash sales, inbound/outbound deliveries, returns, and billing
- Configured Order Management scenarios including cash sales, make-to-order, follow-up orders, and automatic partner determination
- Defined sales document types, number ranges, item category groups, and item categories to streamline order processing across all business units

### Advanced Pricing Architecture
- Developed complex pricing procedures covering the full condition technique stack: condition types, access sequences, condition tables, and condition records
- Designed and configured special condition types for Experian's service-based pricing model — including contract-specific pricing, volume-based discounts, and surcharge structures
- Configured free goods determination, credit/debit note procedures, and condition exclusion groups
- Maintained condition records for global pricing consistency across multiple sales organisations
- Implemented listing and exclusion logic and material determination with condition technique

### Contract & Billing Management
- Configured comprehensive billing setup: billing document types (F2, RE, G2, L2), invoice lists, billing plans (milestone and periodic), copy controls, and output determination
- Delivered service contract management: service contracts, quantity/value contracts, and recurring billing scenarios
- Implemented milestone billing for project-based services integrated with PS (Project Systems)
- Configured intercompany billing procedures and third-party order processing

### Logistics Execution
- Oversaw full Logistics Execution process — inbound and outbound deliveries, shipping types, transportation zones, transportation groups, and route determination
- Configured shipping point determination and route determination to optimise distribution and delivery efficiency
- Configured picking and packing processes, delivery types, and output determination
- Managed stock placements and removals using put-away and picking strategies in WM

### S/4HANA Specific Workstreams

**Business Partner Migration**
- Enhanced Business Partner setup to meet S/4HANA requirements — eliminating redundant customer/vendor master records
- Adapted SD master data (customer, material, customer-material info records) and ensured accurate migration and data reconciliation in S/4HANA
- Validated BP roles and groupings for all customer account groups

**Output Management Migration (NACE → BRF+)**
- Configured output management in S/4HANA using BRF+ for SmartForms, print, email, and EDI outputs for sales and billing documents
- Migrated existing NACE-based output determination to S/4HANA Output Management framework

**Advanced ATP (aATP)**
- Designed and tested scenarios for advanced ATP (aATP) and backorder processing available in S/4HANA
- Integrated MM module for availability check using ATP logic to improve order fulfilment accuracy

**Fiori Rollout**
- Supported Fiori app rollout for SD users — mapping legacy SAP GUI transactions to new role-based Fiori tiles
- Provided user guidance and training on new Fiori-based OTC, Billing, and Logistics apps

**Clean Core & Simplification**
- Identified and remediated obsolete or non-compliant SD customisations
- Simplified code base and adopted S/4HANA best practices throughout the SD landscape

### EDI / IDoc Integration
- Implemented and troubleshot ALE integration, partner profiles, and EDI/IDoc interfaces for seamless communication with non-SAP applications
- Managed EDI connectivity for key financial institution partners

### Data Migration & Cutover
- Managed migration of open sales orders, deliveries, and billing documents — ensuring process continuity during cutover
- Coordinated with cross-functional teams to address business process gaps during migration
- Supported data reconciliation and validation of migrated SD master data in S/4HANA

### Testing & Quality Assurance
- Performed rigorous unit, integration, and regression testing across SAP SD/MM/WM processes
- Led defect management: created and maintained issue logs, executed root-cause analysis during testing and hypercare phases

### Analytics & KPIs
- Developed KPIs and analytics for sales order cycle time, delivery performance, and billing efficiency using standard and custom S/4HANA reports

### Training & Hypercare
- Delivered end-user and key-user training — prepared comprehensive process documentation
- Supported hypercare activities post-go-live, resolving issues and stabilising production processes

---

## Key Deliverables

| Deliverable | Description |
|---|---|
| OTC Process Design Document | Full end-to-end OTC configuration design for S/4HANA |
| Pricing Architecture Document | Complete condition technique design and governance |
| BP Migration Mapping | Customer account group → BP grouping/role mapping |
| Output Management Design | BRF+ output determination replacing NACE |
| aATP Configuration | Advanced ATP scenarios for order fulfilment |
| Fiori Role Design | SD user role mapping and tile configuration |
| Test Scripts (SIT/UAT) | Full test coverage across all OTC processes |
| Cutover Runbook | Open document handling and migration sequence |
| Training Materials | End-user guides for S/4HANA SD processes |
| Hypercare Tracker | Incident log and resolution documentation |

---

## Technical Environment

```
SAP Platform:    S/4HANA (Migration from ECC 6.0)
SD Modules:      OTC · Pricing · Billing · LE · WM · Credit Mgmt
Integration:     FI · CO · MM · PS · QM · WM
Output:          BRF+ · SmartForms · EDI/IDoc · ALE
Tools:           HPQC · Solution Manager · SAP Enable Now
Methodology:     SAP Activate · Agile
```

---

## Key Achievements

- ✅ Successfully migrated complex service-based OTC processes from ECC to S/4HANA
- ✅ Eliminated redundant customer/vendor master records through BP conversion
- ✅ Delivered output management migration from NACE to BRF+ framework
- ✅ Implemented aATP for improved order fulfilment accuracy
- ✅ Zero critical pricing errors post go-live through systematic condition technique governance
- ✅ Fiori adoption achieved across all SD user groups

---

## Lessons from This Engagement

1. **Financial services SD landscapes are heavily contract-driven.** Milestone billing and project-based billing (SD-PS integration) need dedicated workshop time — they are not covered in standard OTC FTS workshops.

2. **BRF+ output management requires a separate cutover track.** Output migration from NACE is not a configuration change — it's a redesign. Scope it as a mini-workstream with its own timeline and testing.

3. **aATP adoption changes confirmed delivery dates.** Business users need advance change management — the new confirmed dates may differ from ECC ATP results and can cause confusion if not communicated pre-go-live.

4. **Clean core is a cultural change, not just a technical one.** Business users want their Z-customisations. The conversation about simplification needs to happen in the Explore phase with clear business justification, not during Realize.

---

> *Client name used with professional discretion. All configuration values, system landscape details, and volume data reflect the nature of the engagement. Specific proprietary business rules have been generalised.*
