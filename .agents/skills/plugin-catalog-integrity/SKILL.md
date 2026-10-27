---
name: plugin-catalog-integrity
description: Maintain the plugin marketplace catalog and generated index consistently.
---
# Plugin catalog integrity

- Treat .grok-plugin/marketplace.json as the source of truth and plugin-index.json as generated output; do not hand-edit generated files.
- Ensure each catalog entry points to a real plugin source and has consistent identity, ownership, version, and metadata.
- Preserve the repository distinction between first-party plugins and third-party external_plugins.
- Run the repository's catalog validation and generation checks after any catalog change.
- Keep changes minimal and deterministic; review diffs for unrelated generated churn.
- Do not infer that catalog inclusion means a plugin is secure, endorsed, or compatible.
