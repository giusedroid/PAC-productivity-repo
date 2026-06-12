# Overnight Agent Tasks

This folder contains mock tasks that agents can execute while the user is away.

All tasks use fictional repository data. Agents should work locally, avoid external services unless a task explicitly says otherwise, and leave clear Markdown outputs for review.

## Queue

| Task | Status | Expected output |
| --- | --- | --- |
| `001-northstar-readiness-memo.md` | Ready | Customer readiness memo |
| `002-weekly-dashboard-refresh.md` | Ready | Updated README proposal or patch |
| `003-heliofleet-architecture-options.md` | Ready | Two-option architecture note |
| `004-lumaloop-blocker-analysis.md` | Ready | Blocker analysis and fallback plan |
| `005-papertrail-dr-questionnaire.md` | Ready | Discovery questionnaire |
| `006-weekly-report-from-repo.md` | Ready | New weekly report draft |

## Agent Rules

- Read the referenced files before writing.
- Keep outputs in Markdown.
- Do not invent real customer facts. Invented details are fine only when clearly marked as assumptions.
- Prefer creating draft files under `reports/`, `projects/`, or the relevant customer folder.
- Update `README.md` only when the task explicitly asks for it.
- Summarize completed work at the top of the output file.
