---
name: teable-api-domain-verification
description: Work with the domain-verification endpoints from the Teable App OpenAPI spec. Use when implementing, debugging, or documenting domain-verification API calls, request payloads, response shapes, and auth behavior in Teable integrations.
---

# domain-verification API Skill

Use this skill to implement or troubleshoot `domain-verification` API flows.

## Workflow

1. Read `references/api.md` for endpoint-level details.
2. Read `references/openapi.json` for exact request and response objects.
3. Build client code from `operationId`, method, path, parameters, and body schema.
4. Validate status codes and response schema before shipping changes.

## Notes

- Treat `references/openapi.json` as the source of truth for this tag.
- If an endpoint references shared schemas, resolve them from the global components in the source spec.
