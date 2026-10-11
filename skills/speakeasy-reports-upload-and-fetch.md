---
name: speakeasy-reports-upload-and-fetch
description: Upload a report and retrieve signed URLs for its linting and change reports.
api: openapi/speakeasy-reports-api-openapi.yml
operations:
- uploadReport
- getLintingReportSignedUrl
- getChangesReportSignedUrl
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/speakeasy-reports-api-openapi.yml ; every operationId checked against the contract
---

# speakeasy-reports-upload-and-fetch

Upload a report and retrieve signed URLs for its linting and change reports.

## Steps

1. 1. Call `uploadReport` with the required authentication headers (`x-api-key`, `Authorization: Bearer <token>`, `x-workspace-identifier`) and the report payload.
2. 2. Call `getLintingReportSignedUrl` with the `documentChecksum` path parameter and the same authentication headers to obtain the signed URL for the linting report.
3. 3. Call `getChangesReportSignedUrl` with the `documentChecksum` path parameter and the same authentication headers to obtain the signed URL for the changes report.

## Rules

- Authentication: Include either an API key in the `x-api-key` header, a Bearer token in the `Authorization` header, and/or a workspace identifier in the `x-workspace-identifier` header as required by the endpoint.
- No rate limiting is defined; exhaustion returns no specific HTTP status.
