# Pricing Condition Technique Playbook (SAP SD)

## Goal
Design pricing that is consistent, maintainable, and easy to troubleshoot.

## Standard Build Sequence (High Level)
1. Define business pricing requirements (discounts, surcharges, freight, taxes, rebates if applicable)
2. Create/confirm:
   - Condition types
   - Access sequences
   - Condition tables
   - Pricing procedure
3. Configure determination:
   - Procedure determination
   - Condition exclusion / scales rules (as needed)
4. Create condition records and validate

## Troubleshooting Checklist (Sales Order)
- Confirm pricing procedure determination
- Check condition type sequence and requirement/routine logic (if used)
- Check access sequence order + condition record validity dates
- Confirm scales, exclusions, and rounding settings
- Validate master data (customer/material/pricing group assignments)

## Best Practices
- Keep naming and purpose clear per condition type
- Avoid “duplicate rules” that overlap without governance
- Maintain a small pricing scenario matrix for regression testing
