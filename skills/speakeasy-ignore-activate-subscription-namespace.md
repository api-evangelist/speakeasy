---
name: speakeasy-ignore-activate-subscription-namespace
description: Ignore a namespace for a subscription and then reactivate it.
api: openapi/speakeasy-subscriptions-api-openapi.yml
operations:
- ignoreSubscriptionNamespace
- activateSubscriptionNamespace
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/speakeasy-subscriptions-api-openapi.yml ; every operationId checked against the contract
---

# speakeasy-ignore-activate-subscription-namespace

Ignore a namespace for a subscription and then reactivate it.

## Steps

1. 1. Call `ignoreSubscriptionNamespace` with the path parameters `subscriptionID` and `namespaceName`.
2. 2. Call `activateSubscriptionNamespace` with the same `subscriptionID` and `namespaceName` to reactivate the ignored namespace.

## Rules

- Authentication: include one of the required headers – `x-api-key` (APIKey), `Authorization: Bearer <token>` (Bearer), or `x-workspace-identifier` (WorkspaceIdentifier).
