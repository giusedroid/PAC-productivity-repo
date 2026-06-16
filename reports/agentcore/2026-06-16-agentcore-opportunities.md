# Monthly Business Review: AgentCore Opportunities

**Date:** 2026-06-16
**Period:** June 2026
**Scope:** Accounts with AgentCore candidate signals only

---

## Executive Summary

Three accounts have AgentCore candidate signals this month: Northstar Bakes, HelioFleet Services, and LumaLoop Retail. Each has a distinct agentic workload opportunity, but all share a common prerequisite: data access and quality must be proven before any agent workflow is positioned.

- **Northstar Bakes** is closest to readiness — pending analytics POC completion.
- **HelioFleet Services** is a strong fit but blocked on telemetry vendor API confirmation.
- **LumaLoop Retail** has the clearest business pain but the hardest data access blocker.

No account has committed to AgentCore. All opportunities are exploratory.

---

## Account Movement

| Customer | Prior Status | Current Status | Movement |
| --- | --- | --- | --- |
| Northstar Bakes | Discovery | Discovery — AgentCore candidate identified | Forward |
| HelioFleet Services | Evaluating | Evaluating — AgentCore candidate identified | Forward |
| LumaLoop Retail | Blocked | Blocked — AgentCore candidate identified (contingent) | Lateral |

- **Northstar Bakes:** AgentCore opportunity identified on 2026-06-15 for a campaign performance analyst agent. Depends on analytics foundation (S3 + Athena + QuickSight POC) being proven first.
- **HelioFleet Services:** AgentCore opportunity identified on 2026-06-15 for a solar maintenance triage assistant. Depends on telemetry vendor API access.
- **LumaLoop Retail:** AgentCore opportunity identified on 2026-06-15 for a merchandising/replenishment assistant. Contingent on resolving POS data export blocker or establishing CSV fallback.

---

## Revenue Metrics

All financial figures below are mock assumptions — no revenue data exists in source files.

| Customer | Current ARR | Current MRR | Projected YoY | Expansion Opportunity | Confidence |
| --- | ---: | ---: | ---: | --- | --- |
| Northstar Bakes | Assumption: GBP 36,000 | Assumption: GBP 3,000 | Assumption: +28% | AgentCore analytics agent add-on after POC | Medium |
| HelioFleet Services | Assumption: GBP 60,000 | Assumption: GBP 5,000 | Assumption: +35% | AgentCore maintenance triage agent | Medium-Low |
| LumaLoop Retail | Assumption: GBP 24,000 | Assumption: GBP 2,000 | Assumption: +15% | AgentCore replenishment assistant (blocked) | Low |

**Notes:**

- Northstar Bakes expansion depends on POC converting to production analytics, then layering AgentCore.
- HelioFleet expansion assumes telemetry integration unlocks both IoT platform spend and AgentCore agent licensing.
- LumaLoop expansion is speculative until data access is resolved.

---

## Forecast Impact

| Customer | Impact | Reason |
| --- | --- | --- |
| Northstar Bakes | Positive | Analytics POC is progressing; AgentCore adds expansion if POC converts. Stakeholder engagement is strong. |
| HelioFleet Services | Neutral | Strong fit but dependent on third-party vendor cooperation. No timeline confirmed for API access. |
| LumaLoop Retail | Negative | POS data blocker unresolved. AgentCore opportunity is contingent on a prerequisite that has not moved. Sponsor impatience is a churn risk. |

---

## Customer Satisfaction Signals

| Customer | Exec Sponsor Sentiment | Delivery Confidence | Product Friction | Recent Signal |
| --- | --- | --- | --- | --- |
| Northstar Bakes | High | Medium | Low — Shopify export inconsistency is minor | Maya engaged in discovery; receptive to phased approach |
| HelioFleet Services | Medium | Medium | Medium — telemetry vendor dependency | Tomas interested but waiting for proof of data access |
| LumaLoop Retail | At risk | Low | High — POS vendor export limits | Priya wants visible movement; patience declining |

---

## Internal KPIs

| KPI | Northstar Bakes | HelioFleet Services | LumaLoop Retail |
| --- | --- | --- | --- |
| Days since last touchpoint | 1 (AgentCore note 2026-06-15) | 1 (AgentCore note 2026-06-15) | 1 (AgentCore note 2026-06-15) |
| Follow-ups completed on time | Yes | Yes | Overdue — escalation not yet actioned |
| Open blockers | 0 | 1 (telemetry volume unconfirmed) | 2 (POS export, fallback plan) |
| Discovery-to-proposal conversion | In progress | Not started | Blocked |
| POC readiness | High — historical CSV data available | Low — awaiting vendor API confirmation | Low — no usable data pipeline |
| AgentCore candidates identified | 1 | 1 | 1 |

---

## Risks and Blockers

| # | Customer | Risk / Blocker | Severity | Mitigation |
| --- | --- | --- | --- | --- |
| 1 | LumaLoop Retail | POS vendor does not provide automated or store-level SKU exports | High | Escalate with vendor; design CSV-to-S3 fallback workflow |
| 2 | LumaLoop Retail | Sponsor impatience may lead to disengagement | Medium | Reframe phase one as data foundation with visible quick wins |
| 3 | HelioFleet Services | Telemetry vendor API access and data volume unconfirmed | Medium | Identify first vendor API; request sample payload this month |
| 4 | HelioFleet Services | Integration partner may be needed for field service write-back | Low | Defer write-back; start with read-only anomaly agent |
| 5 | Northstar Bakes | Shopify export inconsistency could delay POC | Low | Use historical CSV exports as stable fallback for POC |

---

## Decisions or Asks

1. **LumaLoop Retail:** Decision needed — should we proceed with the CSV fallback plan independently, or wait for vendor escalation response? Recommend: proceed with fallback in parallel.
2. **HelioFleet Services:** Ask — can we get internal support to engage the telemetry vendor for a sample API call this month?
3. **All accounts:** Confirm positioning guidance — AgentCore should remain exploratory and not be quoted in any customer proposals until data prerequisites are met.

---

## Next-Month Actions

| Customer | Action | Owner | Target |
| --- | --- | --- | --- |
| Northstar Bakes | Complete analytics POC with historical CSV exports | SA | End of June |
| Northstar Bakes | Draft AgentCore campaign summary agent brief for internal review | SA | Early July |
| HelioFleet Services | Confirm telemetry volume and first vendor API fields | SA | End of June |
| HelioFleet Services | Build read-only anomaly explanation prototype scope | SA | Mid-July |
| LumaLoop Retail | Escalate POS data export options with vendor | SA | Immediate |
| LumaLoop Retail | Design and document CSV-to-S3 fallback workflow | SA | End of June |
| LumaLoop Retail | Re-engage Priya with reframed phase-one narrative | SA | This week |
