# Agentic Workload Candidate: HelioFleet Services

Date: 2026-06-15

## SA Observation

HelioFleet Services is a strong candidate for agentic operations support if telemetry access can be solved.

The customer has a natural decision loop: inspect telemetry, compare against asset history, decide whether a field visit is needed, create or update a maintenance ticket, and produce an uptime explanation for customers. Today this work is spread across vendor dashboards, Jira Service Management, and a legacy SQL Server asset database.

## Candidate AgentCore Use Case

Solar maintenance triage assistant.

The agent could help operations teams:

- Review telemetry anomalies across inverter and panel data.
- Correlate anomalies with asset age, location, and maintenance history.
- Recommend whether to create a Jira maintenance ticket.
- Draft a technician briefing with likely causes and context.
- Generate a customer-facing uptime explanation after review.

## Why AgentCore Might Fit

- The workflow spans multiple systems and requires contextual reasoning.
- The agent could orchestrate read-only checks before recommending an action.
- Human approval can remain mandatory before ticket creation or customer communication.
- The use case has measurable value: fewer unnecessary visits and faster response to underperforming sites.

## Readiness Signals

- Confirm telemetry volume and vendor API access first.
- Start with a read-only anomaly explanation agent before any write-back workflow.
- Treat Jira ticket creation as a later controlled action after the recommendation quality is trusted.

## Open Questions

- Which telemetry fields are available from the first vendor API?
- What anomaly thresholds does operations already trust?
- Should recommendations be optimized for cost, uptime, or technician availability?
