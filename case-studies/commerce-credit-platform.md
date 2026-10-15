# Commerce & Credit Platform

## Overview

A production-oriented commerce platform for inventory, sales, credit, orders and catalog workflows. The system supports different operational roles and combines product management with business rules around payments, financing and device-level inventory.

## Engineering focus

- **Frontend / application:** Next.js, React and TypeScript.
- **Backend / data:** Supabase with PostgreSQL-backed application data.
- **Validation:** Zod and explicit input rules.
- **Product workflows:** inventory, catalog, sales, installment credit, orders and role-aware operations.
- **Device workflows:** QR/barcode handling, labels, product identification and battery-health data.
- **Reporting / operations:** PDF generation, Excel export and printing-related utilities.

## Quality and verification

The project includes dedicated validation commands for:

- Type checking.
- Linting.
- Sale validation.
- Credit logic.
- Sales flows.
- Catalog behavior.
- Interface flows.
- Production build verification.

Several tests use controlled data and simulated services so validation can run without writing production sales or payments.

## What this project demonstrates

This project represents **Full-Stack Product Engineering** rather than a simple CRUD application. The main engineering value is the combination of user-facing workflows, domain rules, validation, data access, reporting and operational tooling in one system.

It demonstrates practical experience with:

- Complex business rules.
- Type-safe web development.
- Data validation.
- Role-aware application flows.
- Product and inventory operations.
- Testing and release verification.

> The complete source repository remains private because it contains production/commercial implementation details.
