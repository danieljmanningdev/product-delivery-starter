# UX Schemas

This directory can contain JSON Schema definitions for projects that document UX artifacts as structured data.

Structured UX documentation is optional. Use it when machine validation, consistency or traceability provides enough value to justify the additional structure.

## Suggested Artifacts

- `screen.schema.json`
- `component.schema.json`
- `flow.schema.json`

## Suggested Identifiers

- Screens: `SCR-*`
- Components: `CMP-*`
- Flows: `FLOW-*`
- Requirements: `FR-*`, `NFR-*`

## Example Screen Document

```json
{
  "id": "SCR-LOGIN",
  "name": "Log in",
  "purpose": "Allow an existing user to authenticate.",
  "route": "/login",
  "components": ["CMP-AUTH-FORM"],
  "states": ["default", "validation-error", "server-error"],
  "status": "designed"
}
```

## Principles

- Schemas should validate useful product rules, not merely make JSON verbose.
- Keep identifiers stable once referenced elsewhere.
- Prefer enums when a project has a genuinely controlled vocabulary.
- Do not force implementation details into UX schemas unless they improve traceability.
- Version schema changes that would invalidate existing documents.
