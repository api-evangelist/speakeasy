---
name: speakeasy-create-and-retrieve-organization
description: Create a new organization and then retrieve its details.
api: openapi/speakeasy-organizations-api-openapi.yml
operations:
- createOrganization
- getOrganization
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/speakeasy-organizations-api-openapi.yml ; every operationId checked against the contract
---

# speakeasy-create-and-retrieve-organization

Create a new organization and then retrieve its details.

## Steps

1. 1. Call `createOrganization` with the required request body fields as defined in the contract.
2. 2. Call `getOrganization` with the path parameter `organizationID` returned from the previous step.

## Rules

- Include the API key in the `x-api-key` header (APIKey scheme).
- Include the workspace identifier in the `x-workspace-identifier` header if required (WorkspaceIdentifier scheme).
