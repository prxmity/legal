# Proximity Legal

Public legal-content repository for Proximity clients.

This repository hosts versioned legal documents and a `config.json` entrypoint that clients can fetch directly from GitHub raw URLs.

Current content is draft material intended for integration, staging, and UI verification while final legal review is still pending.

`config.json` is a strict client contract. Every document entry must always include:
`id`, `title`, `version`, `effectiveDate`, `url`, `previousUrl`, `previousVersion`, `requiresReAcceptance`.
If a document has no previous version, set `previousUrl` and `previousVersion` to `null` instead of omitting them.
