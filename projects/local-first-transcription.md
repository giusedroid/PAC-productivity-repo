# Project: Local-First Transcription Workflow

## Purpose

Design a cautious transcription workflow for fictional sales meetings.

## Principles

- Recordings stay local and are ignored by Git.
- Transcription is manually triggered.
- Raw transcripts go to `transcripts/raw/` and are reviewed before any curated summary is committed.
- Notes should avoid secrets, credentials, and real customer data.

## Candidate Workflow

1. Drop a fictional recording into `recordings/`.
2. Run a local MCP tool or script manually.
3. Review the raw transcript.
4. Commit only a curated Markdown summary.

## Exercise Ideas

- Ask Kiro to draft the MCP server interface.
- Ask Kiro to summarize a mock transcript into customer notes.
- Ask Kiro to identify follow-up actions and risks.
