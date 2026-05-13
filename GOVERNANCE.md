# LUVO Documentation Governance

LUVO DOS is mandatory infrastructure. Documentation is not optional support material; it is the operational contract for product, engineering, AI and operations.

## Production Gate

No module enters production without:

- Product Sheet
- Technical Sheet
- Changelog
- Ownership
- Status
- Version
- Dependencies
- Related workflows
- Prompt registry entries when AI is involved
- ADR when architecture changes

## Authority

Canonical docs override sprint notes, chat outputs, prompts and temporary implementation notes.

## Enforcement

Pull requests touching production modules must reference canonical docs and update them when logic changes.
