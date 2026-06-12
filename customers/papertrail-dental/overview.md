# PaperTrail Dental

## Account Snapshot

- Industry: Dental practice group
- Size: 9 clinics, 115 employees
- Location: Leeds, UK
- Primary contact: Dr. Elaine Brooks, Managing Partner
- Commercial stage: Proposal
- Opportunity theme: Backup, compliance, and disaster recovery

## Business Context

PaperTrail Dental has grown through acquisitions. Each clinic has slightly different backup practices, and the leadership team wants a consistent recovery plan before acquiring more sites.

## Current Environment

- Practice management software hosted per clinic
- Local file servers for scans and documents
- Microsoft 365 for email and shared files
- Manual backup checks

## Customer Goals

- Standardize backup policies across clinics.
- Reduce recovery uncertainty.
- Document a disaster recovery process.
- Avoid a disruptive system replacement.

## AWS Fit

- AWS Backup for supported workloads
- Amazon S3 with Object Lock for immutable backup copies
- AWS Storage Gateway for hybrid file workflows
- AWS Elastic Disaster Recovery for priority servers
- AWS Well-Architected review focused on reliability and security

## Risks

- Sensitive healthcare-adjacent data requires careful handling.
- Some clinic servers may be unsupported or poorly documented.
- RTO and RPO targets are not yet agreed.

## Next Actions

- Run a lightweight Well-Architected review.
- Confirm recovery time and recovery point objectives.
- Prepare a phased proposal starting with backup inventory.
