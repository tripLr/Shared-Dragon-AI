---
name: inspect-grok-memory
description: Examine the current running Grok memory, compare with timestamped backups in My-Dragon-AI, offer backup / revert / Baby Dragon, and support section-by-section review and editing so the user keeps full agency. Always ask to backup before any edit or Baby Dragon. Triggers on inspect grok memory, examine memory, backup memory, revert memory, baby dragon, memory inspector, review memory, or similar.
---

# Inspect Grok Memory Skill

Safety, review, and agency skill for the durable memory that Grok uses.

**Skill location:** Train-Your-Dragon-AI (public) / Shared-Dragon-AI (backup)  
**Private memory backups location:** My-Dragon-AI / memory-backups/

## Purpose

Give the user full control over the running memory:
- See what is currently active
- Review it section by section
- Edit or remove sections
- Create timestamped backups
- Revert to a previous version
- Start fresh (Baby Dragon) without losing core system knowledge

## Core Safety Rule

**Always ask the user to create a backup before any edit or before running Baby Dragon.**  
Do not force it — ask. The user decides.

## Main Flow

1. Show overview of current running memory (top-level headings)
2. Compare with GitHub backup (show latest timestamp)
3. Present choices:
   - **A. Review & Edit sections** (ask backup before any edit/delete)
   - **B. Backup now**
   - **C. Revert** (list available backups)
   - **D. Baby Dragon** (ask backup first; fresh memory that still knows Train Your Dragon + this skill)

### Baby Dragon Concept

Baby Dragon is a **double-blind tool**.  
It works like opening a private browser tab with no history — it lets the user see what a clean/stock memory produces *before* deciding to change the real one.

## Permanent Project Component

This skill and the private memory backup location are permanent parts of the Train Your Dragon system.
