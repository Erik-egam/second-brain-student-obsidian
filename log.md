# Log

Chronological record of wiki changes.

## [2026-04-26] init | Vault setup

## [2026-04-26] install | Obsidian skills

Installed 4 skills:
- obsidian-markdown
- obsidian-bases
- obsidian-cli
- obsidian-vault

## [2026-04-26] ingest | AGENTS.md - Obsidian assistant

Created AGENTS.md with structure for LLM assistants:
- Vault purpose and folder organization
- Workflow for reading, creating, and updating notes
- Link rules (unidirectional allowed, no orphans)
- Index and log update procedures

## [2026-04-26] ingest | index.md

Created index.md with initial catalog of existing pages.

## [2026-04-26] update | index.md

Updated index.md to reflect only existing folders and their content.

## [2026-04-26] update | AGENTS.md

Updated AGENTS.md to match current vault structure (raw/, 005-Books/, etc.).

## [2026-04-26] lint | Health check

Issues found:
- Journal references non-existent templates via wikilinks
- Obsidian.md has no cross-references
- Missing frontmatter in Journal
- Several folders empty

## [2026-04-26] update | AGENTS.md - Cross-references

Added strict cross-reference rules to AGENTS.md:
- All linked pages must exist
- Bidirectional links required
- Related files section in every note
- Index integrity: only pages with connections go to index.md
- No broken links allowed