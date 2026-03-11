# Case Study 2: SAP S/4HANA Public Cloud OTC Implementation — Global Atlantic Financial Group

> **Client:** Global Atlantic Financial Group  
> **Role:** SAP SD / S/4HANA OTC Consultant  
> **Duration:** May 2021 — April 2022 (12 months)  
> **Programme Type:** Full Lifecycle S/4HANA Public Cloud Implementation  
> **Environment:** SAP S/4HANA Public Cloud · ECC 6.0 · SD · FI · CO · MM · PS · EDI  

---

## Executive Summary

Served as OTC functional consultant on Global Atlantic Financial Group's S/4HANA Public Cloud implementation — a technically demanding engagement combining financial services complexity with the constraints and best-practice disciplines of SAP's Public Cloud environment. Delivered end-to-end OTC configuration including project-based billing (SD-PS integration), complex pricing procedures, cloud-compliant customisation, and full integration with FI/CO for revenue recognition.

Global Atlantic's business model — spanning insurance and financial products — required sophisticated contract management, project billing, and revenue recognition capabilities. The Public Cloud constraint meant designing solutions within SAP Best Practices while using SSCUI (Self-Service Configuration UIs) and cloud extensibility tools rather than traditional IMG customisation.

---

## Client Background

Global Atlantic Financial Group is a leading US insurance and financial services company offering retirement and life insurance products. Their SAP implementation covered Order-to-Cash processes for their professional services arm, including:
- Project-based service delivery with milestone billing
- Complex pricing for financial service contracts
- Integration between SD and PS (Project Systems) for resource-related billing
- Revenue recognition aligned to insurance industry requirements

---

## My Scope & Responsibilities

### AS-IS Discovery & Process Analysis
- Conducted process analysis and developed questionnaires to document current business flows across OTC teams
- Facilitated AS-IS workshops across business units — capturing existing process pain points, workarounds, and requirements
- Created business flowcharts and collaborated with stakeholders to lock Order-to-Cash scope
- Developed detailed project plans aligned to SAP Activate Explore phase deliverables

### S/4HANA Public Cloud Configuration
- Worked extensively with S/4HANA Public Cloud features including SSCUI configuration and extensibility tools
- Activated SAP Best Practices scope items for OTC and pricing processes
- Facilitated fit-to-standard workshops to validate scope item coverage against business requirements
- Designed cloud-compliant OTC solutions — eliminating traditional Z-customisations in favour of standard extensibility

### OTC Baseline Configuration
- Led OTC baseline configuration: Global Template (GT) account group setup, customer master layout design, and organisational structure
- Configured order types, item category determination, pricing structures, copy controls, delivery, billing, and account determination
- Configured special business scenarios: drop ship orders, consignment fill-up / issue / pick-up / returns
- Set up outbound delivery documents, delivery item categories, and item category determination rules

### SD–PS Integration (Project-Based Billing)
- Collaborated with Professional Services business teams for project-based billing, resource-related billing, and milestone billing
- Integrated SD with PS for project-based service orders, project billing profiles, and results analysis
- Ensured accurate revenue recognition through PS-SD billing integration
- Configured billing document setup for milestone billing, pro-forma invoices, periodic billing, credit memos, and debit memos

### Complex Pricing Procedures
- Configured complex pricing procedures including condition exclusion groups, custom condition types, and pricing routines
- Maintained condition records for global pricing consistency across the organisation
- Developed custom copy control routines at sales order and delivery levels to meet diverse business requirements
- Configured tax determination rules and material determination logic

### Credit & Risk Management
- Set up credit management functions: defined risk categories, credit groups, and automated credit checks for sales transactions
- Implemented dynamic credit check configuration to protect revenue and manage financial risk

### Partner, Output & Text Determination
- Configured partner determination, output determination, and sales promotions
- Developed SmartForms for order acknowledgements and invoice returns
- Defined text determination strategies, incompletion logs, and product substitution logic

### Route & Logistics Configuration
- Customised route determination, shipping point determination, and plant determination to optimise distribution processes
- Configured logistics execution for the service delivery model

### FI/CO Integration & Revenue
- Coordinated closely with FI and MM to align pricing, account determination, tax configurations, and revenue/CO integration
- Ensured correct revenue recognition postings aligned to insurance industry accounting requirements

### Testing & Quality
- Executed comprehensive testing: unit, system integration, performance, UAT, and regression testing using HPQC
- Ensured robustness and business alignment across all tested scenarios

### Training & Knowledge Transfer
- Led training sessions for business SMEs on new SAP SD S/4HANA functionalities and process enhancements
- Delivered change management support for transition from legacy processes to S/4HANA Public Cloud

---

## Key Deliverables

| Deliverable | Description |
|---|---|
| AS-IS Process Documentation | Current state business process flows |
| Scope Confirmation Document | Validated Best Practices scope items vs requirements |
| OTC Configuration Design | Full S/4HANA Public Cloud OTC configuration |
| SD-PS Billing Design | Project billing and milestone billing configuration |
| Pricing Procedure Design | Complex condition technique for financial services |
| Credit Management Setup | Risk categories and automated credit check rules |
| Test Scripts (HPQC) | Full SIT/UAT coverage |
| Training Deck | SME training materials for S/4HANA Public Cloud |

---

## Technical Environment

```
SAP Platform:    S/4HANA Public Cloud
Configuration:   SSCUI · Best Practices Activation · Cloud Extensibility
Integration:     FI · CO · MM · PS · PI Integration
Tools:           HPQC · Solution Manager · SAP Enable Now · ServiceNow · Panya
EDI:             EDI Standard X12 · IDocs
Methodology:     SAP Activate · Agile · ITIL
```

---

## Key Achievements

- ✅ Delivered S/4HANA Public Cloud OTC implementation within 12-month timeline
- ✅ SD-PS project billing integration working for all milestone and resource-related billing scenarios
- ✅ Configured drop ship and consignment scenarios not typically addressed in financial services implementations
- ✅ Revenue recognition correctly aligned to insurance industry requirements
- ✅ Business SMEs trained and confident on S/4HANA Public Cloud OTC at go-live

---

## What Made This Engagement Distinctive

**Public Cloud constraint as a discipline:**
Working in S/4HANA Public Cloud forces a clean-core discipline that most on-premise implementations avoid. Every configuration decision had to be justified against the standard — there was no "just build a Z-program" escape route. This made the design cleaner and the solution more maintainable long-term.

**Financial services OTC complexity:**
Global Atlantic's OTC is not a standard product sales model. Service contracts, milestone billing, PS integration, and insurance-specific revenue recognition requirements make this a significantly more complex engagement than a typical manufacturing SD implementation. Understanding the SD-PS-FI triangle deeply was essential.

**AS-IS discipline in a greenfield:**
Even on a greenfield implementation, disciplined AS-IS discovery prevents scope gaps. The workshops we ran at the start surfaced 12 process requirements that were not covered by standard Best Practices scope — these were addressed early rather than becoming late-stage change requests.

---

> *Client name used with professional discretion. All configuration values, system landscape specifics, and business process details reflect the nature and scope of the engagement.*
