# HelioFleet Services

## Account Snapshot

- Industry: Commercial solar maintenance
- Size: 140 employees
- Location: Manchester, UK
- Primary contact: Tomas Reid, Operations Director
- Commercial stage: Evaluating
- Opportunity theme: IoT telemetry and predictive maintenance

## Business Context

HelioFleet maintains rooftop solar installations for supermarkets and light industrial sites. Field teams currently inspect sites on fixed schedules, even when telemetry could reveal which locations need attention.

## Current Environment

- Device telemetry arrives through vendor dashboards.
- Maintenance tickets are tracked in Jira Service Management.
- Asset records live in a legacy SQL Server database.

## Customer Goals

- Consolidate inverter and panel telemetry.
- Detect underperforming sites earlier.
- Reduce unnecessary maintenance visits.
- Produce customer-facing uptime reports.

## AWS Fit

- AWS IoT Core for device ingestion if vendors can publish MQTT
- Amazon Kinesis Data Firehose for streaming delivery
- Amazon Timestream or Amazon S3 for time-series history
- AWS Lambda for alerting rules
- Amazon QuickSight for uptime reporting

## Risks

- Telemetry access depends on third-party device vendors.
- Data volume is not yet estimated.
- The customer may need an integration partner for field service automation.

## Next Actions

- Confirm expected telemetry frequency and device count.
- Build two architecture options: minimal batch ingest and near-real-time alerting.
- Identify the first vendor API to test.
