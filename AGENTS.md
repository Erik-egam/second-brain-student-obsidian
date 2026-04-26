---
title: AGENTS.md
date: 2026-04-26
tags:
  - metadata
  - agent
aliases:
  - Assistant Instructions
---

# AGENTS.md

Instructions for LLM assistants working with this Obsidian vault.

## Vault Purpose

This vault serves as a personal knowledge management system organized into categories:

- **001-Journal/** — Daily reflections and learning logs
- **002-University/** — Academic work for Semester 6
- **003-Autonomous learning/** — Self-directed learning notes
- **004-Projects/** — Personal projects
- **005-Books/** — Book notes and summaries
- **Templates/** — Reusable note templates
- **raw/** — External sources (articles, papers)

## Working with This Vault

### Reading Files

Always read `index.md` first to understand vault structure and existing notes. Check `log.md` for recent changes.

### Creating Notes

1. Use appropriate templates for the note type
2. Add frontmatter with `title`, `date`, and `tags`
3. Link to related notes using `[[wikilinks]]`
4. Include summaries in index.md tables

### Updating Index

When adding new notes, update index.md:

- Add entry to the appropriate category table
- Include a brief summary (1-2 sentences)
- Link via wikilink to the new note

### Recording Changes

All changes must be logged in `log.md`:

```markdown
## [YYYY-MM-DD] <action> | <description>

Details of the change.
```

Common actions:
- `create` — New note created
- `update` — Existing note modified
- `delete` — Note removed
- `ingest` — External content imported

## Link Rules

### Connections

- Links can be **unidirectional** (A links to B, B doesn't need to link back)
- Every note must have at least one connection to another note
- No orphan files allowed

### Index Integrity

Only notes with connections appear in index.md:
- Notes without links are considered orphans
- Remove orphaned notes from index tables during updates

### Broken Links

- Never create links to non-existent notes
- Before linking, verify the target note exists
- Use index.md to check for existing notes

## Related Files

- [[index]] — Vault catalog
- [[log]] — Change history