# Shared-Dragon-AI

**Shareable skills and versioned backups for the Train Your Dragon system.**

This repository holds recoverable copies of the skills created and running in the personal Train Your Dragon environment.

## Purpose

- Versioned backup of custom skills
- Recovery source if a local environment is lost or reset
- Shareable components (when deliberately published)

## Current Status

**Durability test in progress** (started 2026-07-22).

This is an active test of making the Train Your Dragon skill layer durable across instances.

## Structure

```
Shared-Dragon-AI/
├── README.md
├── skills/                    ← current skill definitions
│   └── (individual SKILL.md files)
└── versions/                  ← dated snapshots
    └── 2026-07-22/
```

## Relationship

- **My-Dragon-AI** (private) — memory backups, history, my-research
- **Train-Your-Dragon-AI** (public) — philosophy and method
- **Shared-Dragon-AI** (this repo) — skill backups and shareable components
