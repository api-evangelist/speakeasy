---
name: speakeasy-create-workspace
description: Create a new workspace and configure its basic settings.
api: openapi/speakeasy-workspaces-api-openapi.yml
operations:
- createWorkspace
- updateWorkspaceSettings
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/speakeasy-workspaces-api-openapi.yml ; every operationId checked against the contract
---

# speakeasy-create-workspace

Create a new workspace and configure its basic settings.

## Steps

1. 1. Call `createWorkspace` with the required request body fields (e.g., name, description).
2. 2. Call `updateWorkspaceSettings` with the `workspace_id` returned from step 1 and provide the settings fields to configure the workspace.

## Rules

- Auth: Include the API key in the `x-api-key` header for all requests.
- Idempotency: `createWorkspace` is not idempotent; avoid duplicate calls.
- Errors: On failure, the API returns standard HTTP error codes (4xx for client errors, 5xx for server errors).
