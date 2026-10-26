# Agent guidance — plugin-marketplace

This repository is a plugin catalog. The source of truth is .grok-plugin/marketplace.json; .grok-plugin/plugin-index.json is generated and must not be edited manually.

## Skill routing
- Catalog entries, generated index, schema validation, or plugin source mapping: read .agents/skills/plugin-catalog-integrity/SKILL.md.
- Third-party plugin onboarding, remote sources, versions, hashes, or permissions: read .agents/skills/plugin-supply-chain-review/SKILL.md.

## Validation
Run the repository's catalog validation workflow/scripts after catalog changes. Catalog inclusion is not a security endorsement.
