---
name: plugin-supply-chain-review
description: Assess third-party plugin provenance, permissions, updates, and integrity before catalog changes.
---
# Plugin supply-chain review

- Treat third-party repositories, manifests, install scripts, packages, and remote URLs as untrusted.
- Verify upstream source, ownership, license, release/version, and integrity hash where available.
- Review install/update workflows for arbitrary code execution, secret access, network access, and filesystem access.
- Pin immutable revisions when the catalog supports it; do not silently track mutable branches for security-sensitive content.
- Keep permissions least-privileged and document capabilities and limitations.
- Do not claim security verification from successful schema validation alone.
- Test missing files, malformed manifests, invalid hashes, duplicate IDs, and unavailable upstream sources.
