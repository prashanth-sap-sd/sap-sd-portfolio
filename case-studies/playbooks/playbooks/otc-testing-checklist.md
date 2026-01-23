# OTC Testing & Validation Checklist (SAP SD/LE)

## End-to-End Flow
- Inquiry/Quotation (if used)
- Sales Order creation and checks (partner, pricing, ATP)
- Delivery creation + picking/packing
- PGI
- Billing and accounting touchpoints
- Outputs (print/email/EDI as applicable)

## Common Failure Points to Validate
- Pricing determination
- Shipping point determination
- Route determination
- Incompletion logs
- Copy control (order → delivery, delivery → billing)
- Credit check behavior (if enabled)
- Master data dependencies (customer/material/sales area)

## Test Data Guidance
- Build 3–5 reusable customer/material combos
- Include edge cases: returns, credit/debit memo, partial delivery
