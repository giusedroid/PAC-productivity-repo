# Agentic Workload Candidate: Northstar Bakes

Date: 2026-06-15

## SA Observation

Northstar Bakes looks like a good early candidate for an agentic analytics assistant once the first S3, Athena, and QuickSight proof of concept is in place.

The customer has recurring questions after each campaign, but the team currently answers them manually by combining Shopify exports, product margin spreadsheets, and email context. This creates a repeatable analysis loop that could eventually be assisted by an agent.

## Candidate AgentCore Use Case

Campaign performance analyst for ecommerce launches.

The agent could help the digital operations team:

- Compare current campaign performance against prior launches.
- Identify products with unusual margin or conversion movement.
- Draft a same-day campaign summary for Maya and Owen.
- Suggest follow-up questions when data quality is incomplete.
- Prepare a concise narrative for leadership without requiring spreadsheet work.

## Why AgentCore Might Fit

- The workflow is repetitive and evidence-based.
- Inputs are mostly structured or semi-structured once exports land in S3.
- The business wants faster insight, not just dashboards.
- The agent can start in read-only mode and produce draft recommendations for human review.

## Readiness Signals

- First priority should remain the analytics foundation.
- AgentCore should be introduced after data freshness and schema consistency are proven.
- A safe first milestone would be a weekly campaign summary agent using historical exports only.

## Open Questions

- Which campaign KPIs does Maya trust most?
- Can product margin data be refreshed without manual spreadsheet cleanup?
- Should the agent produce internal notes only, or customer-facing marketing recommendations later?
