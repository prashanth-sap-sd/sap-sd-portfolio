# Case Study 02 — Pricing Procedure Design & Troubleshooting (Sanitized)

## Context
- Focus: complex pricing with discounts/surcharges, exclusions, and master data governance
- Role: SAP SD Consultant
- Note: Values and identifiers removed for confidentiality

## Business Challenge
Pricing outcomes were inconsistent due to overlapping condition records, unclear access sequencing, and missing governance on maintenance. Users reported “wrong price” issues that were hard to reproduce.

## What I Did (Approach)
1. **Pricing architecture review**
   - Checked pricing procedure design, condition types, access sequences, and determination order.
2. **Master data governance**
   - Defined which teams own which condition records and added validation steps before production moves.
3. **Root cause playbook**
   - Standardized troubleshooting steps for VK11/VK12/VK13 maintenance and document-level analysis.
4. **Testing pack**
   - Built a scenario matrix for common pricing outcomes (customer/material/quantity/date validity).

## What I Delivered (High Level)
- Clear “rule map” for pricing determination (what wins, where, and why)
- Standard investigation path for pricing issues
- Reduced repeated incidents by aligning design + maintenance process

## Lessons Learned
- Most pricing defects are governance + data + sequence issues, not “just configuration”
- A small test matrix catches 80% of pricing issues early
