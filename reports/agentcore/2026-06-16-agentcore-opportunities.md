# Monthly Business Review: AgentCore Opportunities

**Report date:** 2026-06-16
**Period:** June 2026
**Scope:** Accounts with AgentCore candidate signals only

---

## Executive Summary

Three accounts show AgentCore candidate signals this month: Northstar Bakes, HelioFleet Services, and LumaLoop Retail. All three have identifiable repeatable decision loops that could benefit from agentic assistance. None are positioned as committed — each requires prerequisite work (data access, telemetry confirmation, or analytics foundation) before AgentCore engagement moves forward. HelioFleet is the strongest near-term candidate if telemetry access is confirmed. Northstar is a natural second mover once the analytics POC proves data freshness. LumaLoop is blocked until POS data export is resolved.

---

## Account Movement

| Account | Prior Status | Current Status | Movement |
| --- | --- | --- | --- |
| Northstar Bakes | Discovery | Discovery — AgentCore candidate identified | Forward |
| HelioFleet Services | Evaluating | Evaluating — AgentCore candidate identified | Forward |
| LumaLoop Retail | Blocked | Blocked — AgentCore candidate identified, contingent on data access | Lateral |

---

## Revenue Metrics

All revenue figures below are mock assumptions. No confirmed financials exist in source notes.

| Customer | Current ARR | Current MRR | Projected YoY | Expansion Opportunity | Forecast Impact | Confidence |
| ---: | ---: | ---: | ---: | --- | --- | --- |
| Northstar Bakes | Assumption: GBP 36,000 | Assumption: GBP 3,000 | Assumption: +28% | AgentCore analytics assistant after POC | Positive | Medium |
| HelioFleet Services | Assumption: GBP 60,000 | Assumption: GBP 5,000 | Assumption: +35% | AgentCore maintenance triage assistant | Positive | Medium-High |
| LumaLoop Retail | Assumption: GBP 24,000 | Assumption: GBP 2,000 | Assumption: +15% | AgentCore merchandising assistant if data unblocked | Neutral (blocked) | Low |

**Renewal / retention risk:** None flagged this month. All three accounts remain engaged.

---

## Forecast Impact

| Customer | Category | Reason |
| --- | --- | --- |
| Northstar Bakes | Positive | Analytics POC conversion would create a natural path to AgentCore expansion; campaign analyst agent is a strong upsell once data foundation is proven |
| HelioFleet Services | Positive | Telemetry triage agent addresses a measurable cost problem (unnecessary site visits); strong executive sponsor engagement |
| LumaLoop Retail | Neutral | POS data blocker prevents any forward movement; forecast unchanged until export path is resolved or fallback CSV workflow is accepted |

---

## Customer Satisfaction Signals

| Customer | Delivery Confidence | Executive Sponsor Sentiment | Product Friction | Recent Feedback |
| --- | --- | --- | --- | --- |
| Northstar Bakes | High | High — Maya engaged in discovery and open to POC | Low | Positive response to analytics-first framing |
| HelioFleet Services | Medium | Medium — Tomas supportive but waiting on telemetry confirmation | Medium — vendor API access unclear | Interested but cautious on timeline |
| LumaLoop Retail | Low | At risk — Priya wants visible movement; patience declining | High — POS vendor export limits | Frustrated by lack of progress on data access |

---

## Internal KPIs

| KPI | Northstar Bakes | HelioFleet Services | LumaLoop Retail |
| --- | --- | --- | --- |
| Days since last customer touchpoint | 1 (AgentCore note 2026-06-15) | 1 (AgentCore note 2026-06-15) | 1 (AgentCore note 2026-06-15) |
| Follow-ups completed on time | Yes | Pending — telemetry volume unconfirmed | Overdue — escalation not yet sent |
| Open blockers | 0 | 1 (telemetry vendor access) | 1 (POS data export) |
| Discovery-to-proposal conversion | In progress | Waiting on prerequisite | Stalled |
| POC readiness | High — historical exports available | Medium — depends on vendor API | Low — data not accessible |
| Architecture review completion | Not yet started | Two options drafted (batch/real-time) | Not applicable until data unblocked |
| Agentic workload candidates identified | 1 (campaign performance analyst) | 1 (solar maintenance triage assistant) | 1 (merchandising replenishment assistant) |

---

## AgentCore Candidate Detail

### Northstar Bakes — Campaign Performance Analyst

- **Candidate workload:** Automated same-day campaign summary comparing current vs. prior launches
- **Business problem:** Manual spreadsheet work combining Shopify exports, margin data, and email context
- **Adoption readiness:** Medium — depends on analytics POC proving data freshness and schema consistency
- **Data/integration prerequisites:** S3 landing zone, Athena queries, historical campaign exports
- **Human approval points:** All outputs remain draft summaries for Maya and Owen to review
- **Revenue expansion path:** Analytics foundation → AgentCore campaign analyst → personalisation recommendations

### HelioFleet Services — Solar Maintenance Triage Assistant

- **Candidate workload:** Anomaly review, asset correlation, maintenance ticket recommendation, technician briefing
- **Business problem:** Manual cross-system inspection across vendor dashboards, Jira, and legacy SQL Server
- **Adoption readiness:** Medium-High — natural decision loop exists; waiting on telemetry API confirmation
- **Data/integration prerequisites:** Vendor telemetry API access, Jira Service Management read access, asset DB connectivity
- **Human approval points:** Ticket creation and customer-facing communication require human sign-off
- **Revenue expansion path:** Read-only anomaly agent → ticket recommendation → full predictive maintenance workflow

### LumaLoop Retail — Merchandising Replenishment Assistant

- **Candidate workload:** Weekly replenishment recommendations combining store sales, ecommerce demand, and inventory signals
- **Business problem:** Manual, spreadsheet-heavy buying decisions; stockouts on fast-moving products
- **Adoption readiness:** Low — blocked by POS data export limitations
- **Data/integration prerequisites:** Store-level SKU sales exports, inventory refresh cadence, product category prioritisation
- **Human approval points:** All buying and stock transfer decisions require Priya's approval
- **Revenue expansion path:** CSV fallback → data quality agent → replenishment assistant → demand forecasting

---

## Risks and Blockers

| Risk | Account | Severity | Mitigation |
| --- | --- | --- | --- |
| POS vendor refuses automated export | LumaLoop Retail | High | Propose scheduled CSV upload fallback to S3; reframe as data foundation, not forecasting |
| Telemetry vendor API unavailable or limited | HelioFleet Services | Medium | Start with batch file ingest; confirm fields available before committing to real-time architecture |
| Analytics POC delays AgentCore timeline | Northstar Bakes | Low | AgentCore is positioned as a follow-on; no commitment made |
| Sponsor patience declining | LumaLoop Retail | Medium | Deliver visible progress on fallback workflow even if primary export path is stalled |

---

## Decisions or Asks

1. **LumaLoop Retail:** Approve escalation to POS vendor account manager for export API discussion. If denied, approve fallback CSV workflow as interim path.
2. **HelioFleet Services:** Confirm whether integration partner budget is available if vendor API requires middleware.
3. **Northstar Bakes:** No decision needed — proceeding with analytics POC as planned; AgentCore remains a follow-on conversation.

---

## Next-Month Actions

| Account | Action | Owner | Target |
| --- | --- | --- | --- |
| Northstar Bakes | Complete analytics POC with historical exports; validate data freshness | SA | End of June |
| Northstar Bakes | Share AgentCore campaign analyst concept with Maya once POC results are available | SA | Early July |
| HelioFleet Services | Confirm telemetry volume and first vendor API fields | SA | End of June |
| HelioFleet Services | Draft read-only anomaly explanation agent scope document | SA | Mid-July |
| LumaLoop Retail | Send POS vendor escalation email | SA | This week |
| LumaLoop Retail | Prepare CSV fallback architecture option for Priya | SA | End of June |
| All | Update AgentCore opportunity tracker with readiness scores | SA | Monthly |
