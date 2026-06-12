# LumaLoop Retail

## Account Snapshot

- Industry: Independent retail chain
- Size: 32 shops, 220 employees
- Location: Cardiff, UK
- Primary contact: Priya Morgan, Commercial Director
- Commercial stage: Blocked
- Opportunity theme: Sales data integration and demand forecasting

## Business Context

LumaLoop sells homeware and lifestyle products across local shops and a small ecommerce channel. The leadership team wants demand forecasting, but store-level sales data is trapped in the POS vendor portal.

## Current Environment

- POS vendor portal with limited export features
- WooCommerce ecommerce site
- Inventory tracked by store managers in spreadsheets
- No centralized data warehouse

## Customer Goals

- Compare store and ecommerce demand.
- Reduce stockouts on fast-moving products.
- Make replenishment decisions weekly instead of monthly.
- Build a foundation for demand forecasting.

## AWS Fit

- Amazon AppFlow if SaaS connectors become available
- S3 data lake for store and ecommerce exports
- AWS Glue DataBrew for early data cleanup
- Amazon Forecast or SageMaker later, once clean history exists

## Risks

- POS vendor only offers manual downloads today.
- Forecasting is premature until data quality improves.
- Customer sponsor is impatient and wants visible movement.

## Next Actions

- Escalate data export options with POS vendor.
- Create a fallback plan using scheduled CSV uploads to S3.
- Reframe phase one as data foundation, not forecasting.
