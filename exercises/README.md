# Exercises

Use these exercises to practice productivity-as-code workflows in Kiro.

## Exercise 1: Customer Summary

Prompt Kiro:

```text
Read customers/northstar-bakes and generate a concise account summary for my manager. Include business trigger, AWS fit, risks, and next actions.
```

Expected output:

- A manager-friendly summary
- Clear assumptions
- No invented real-world facts outside the mock repository

## Exercise 2: README Dashboard Refresh

Prompt Kiro:

```text
Review customers/, projects/, and active/. Update the "What Am I Working On Right Now" table in README.md.
```

Expected output:

- Updated status table
- Concise next actions
- No changes to unrelated sections

## Exercise 3: Migration Readiness Memo

Prompt Kiro:

```text
Using projects/smb-migration-readiness.md and customers/papertrail-dental/overview.md, draft a migration readiness memo in reports/.
```

Expected output:

- Recommendation for a first workload
- Risks and mitigations
- Clear decision needed

## Exercise 4: Local-First Tool Design

Prompt Kiro:

```text
Design a local MCP tool for generating weekly reports from this repository. Do not implement it yet. Create the design in tools/productivity_mcp/design.md.
```

Expected output:

- Local-only design
- Tool inputs and outputs
- Safety assumptions
