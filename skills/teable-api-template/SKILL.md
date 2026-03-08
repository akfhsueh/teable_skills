---
name: teable-api-template
description: Work with the template endpoints from the Teable App OpenAPI spec. Use when implementing, debugging, or documenting template API calls, request payloads, response shapes, and auth behavior in Teable integrations.
---

# template API Skill

Use this skill to implement or troubleshoot `template` API flows.

## Workflow

1. Read `references/api.md` for endpoint-level details.
2. Read `references/openapi.json` for exact request and response objects.
3. Build client code from `operationId`, method, path, parameters, and body schema.
4. Validate status codes and response schema before shipping changes.

## Notes

- Treat `references/openapi.json` as the source of truth for this tag.
- If an endpoint references shared schemas, resolve them from the global components in the source spec.
