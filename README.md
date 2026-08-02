# Fund Administration NAV & Fee Audit

Validate fund-administration invoices and NAV-dependent fees across tiers, classes, transactions, and service obligations.

**Primary buyer:** Asset managers and fund boards. **Evidence:** administration agreements, NAVs, asset tiers, investor accounts, share classes, transactions, performance data, expenses, fee invoices, and payments.

Full local application built with React, Vite, Express, PostgreSQL, and OpenRouter. Includes 15 domain-specific capabilities, 105 custom AI workbench fields, three scenario-fill controls per feature, operational registers, workflow transitions, analytics, professional AI decision briefs, audit history, and at least 15 PostgreSQL records per capability.

## Domain capabilities

- Administration agreement library
- Fund share-class registry
- Daily monthly NAV ingestion
- Asset tier calculation
- Investor account counts
- Transaction volume counts
- Base administration fee
- Fund accounting fee
- Transfer agency fee
- Performance fee support
- Service credit calculation
- Invoice recalculation
- Administrator dispute workflow
- Payment credit reconciliation
- Fund vendor analytics

Run `./start.sh`, then open <http://127.0.0.1:4672>. API: `5672`.

Administrator: `runtime-admin@example.com` / `LocalDemo!2026`. Operator and reviewer credential buttons are available on the login page.
