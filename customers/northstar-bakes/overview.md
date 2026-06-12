# Northstar Bakes

## Account Snapshot

- Industry: Specialty food manufacturing and ecommerce
- Size: 85 employees
- Location: Bristol, UK
- Primary contact: Maya Clarke, Head of Digital Operations
- Commercial stage: Discovery
- Opportunity theme: Ecommerce scalability and sales analytics

## Business Context

Northstar Bakes sells premium baking kits through a Shopify storefront and supplies regional cafes. Seasonal campaigns create traffic spikes that the current reporting stack cannot explain quickly enough.

## Current Environment

- Shopify storefront
- PostgreSQL database hosted by a small managed provider
- Manual CSV exports into spreadsheets
- Email-based customer support workflow

## Customer Goals

- Understand campaign performance within the same business day.
- Reduce manual reporting work.
- Improve storefront resilience during holiday promotions.
- Create a path toward personalized offers without rebuilding the storefront.

## AWS Fit

- Amazon S3 for landing exported sales and product data
- AWS Glue for light transformation
- Amazon Athena for query access
- Amazon QuickSight for dashboards
- Amazon CloudFront for static campaign assets

## Risks

- Data exports are inconsistent across Shopify apps.
- Small operations team may struggle with too many services at once.
- Customer wants quick wins before any platform migration.

## Next Actions

- Draft a migration readiness memo focused on analytics first.
- Propose a two-week proof of concept using historical CSV exports.
- Confirm whether Shopify webhooks are available on their current plan.
