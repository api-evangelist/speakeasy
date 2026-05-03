# Speakeasy

The platform to build APIs your users love. Speakeasy provides best-in-class API tooling for generating robust SDKs, API documentation, Terraform providers, MCP servers, and end-to-end contract testing — all OpenAPI-native with no proprietary DSLs.

**URL:** [https://www.speakeasy.com/](https://www.speakeasy.com/)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

AI, Documentation, MCP, Platform, SDKs, Terraform, Testing

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-02

## Products

| Product | Description |
|---|---|
| [SDK Generation](https://www.speakeasy.com/product/sdk-generation) | Generate idiomatic, type-safe SDKs in 8+ languages from OpenAPI specs |
| [Terraform Generation](https://www.speakeasy.com/product/terraform-generation) | Turn your OpenAPI spec into a production-ready Terraform provider |
| [MCP Server Generation](https://www.speakeasy.com/product/mcp-server) | Generate production-ready MCP server code from OpenAPI specifications |
| [DocsMD](https://www.speakeasy.com/product/api-docs) | Generate beautiful API documentation from OpenAPI specs |
| [Contract Testing](https://www.speakeasy.com/docs/sdk-testing) | API contract test generation using OpenAPI and Arazzo specifications |
| [React Query Hooks](https://www.speakeasy.com/product/react-query) | Generate fully typed TanStack Query hooks from OpenAPI specs |
| [Gram](https://www.speakeasy.com/product/gram) | MCP Cloud platform for hosting, securing, and monitoring AI agents |

## APIs

| API | Base URL | Description |
|---|---|---|
| [Speakeasy API](openapi/speakeasy-openapi.yml) | https://api.prod.speakeasy.com | Platform API for workspace management, SDK artifacts, and generation pipeline |

## Artifacts

### OpenAPI Specifications

- [speakeasy-openapi.yml](openapi/speakeasy-openapi.yml) — Speakeasy platform API covering Auth, Workspaces, Organizations, Artifacts, Code Samples, GitHub integration, and OpenAPI Suggest

### Spectral Rules

- [speakeasy-rules.yml](rules/speakeasy-rules.yml) — Spectral ruleset enforcing Speakeasy API conventions including versioned paths, camelCase operation IDs, and workspace-scoped resource patterns

### Naftiko Capabilities

- [sdk-platform-management.yaml](capabilities/sdk-platform-management.yaml) — Unified REST and MCP capability for SDK platform management workflows (13 tools)

#### Shared Definitions

- [shared/speakeasy.yaml](capabilities/shared/speakeasy.yaml) — Per-API consumed definition for the Speakeasy platform API

### JSON Schema

- [speakeasy-workspace-schema.json](json-schema/speakeasy-workspace-schema.json) — Schema for Speakeasy Workspace resources
- [speakeasy-organization-schema.json](json-schema/speakeasy-organization-schema.json) — Schema for Speakeasy Organization resources

### JSON Structure

- [speakeasy-workspace-structure.json](json-structure/speakeasy-workspace-structure.json) — Structure documentation for Workspace resources and relationships

### JSON-LD

- [speakeasy-context.jsonld](json-ld/speakeasy-context.jsonld) — JSON-LD context mapping Speakeasy vocabulary to linked data semantics

### Examples

- [speakeasy-validate-api-key-example.json](examples/speakeasy-validate-api-key-example.json) — Validate API Key request/response example
- [speakeasy-get-workspaces-example.json](examples/speakeasy-get-workspaces-example.json) — Get Workspaces request/response example
- [speakeasy-get-organizations-example.json](examples/speakeasy-get-organizations-example.json) — Get Organizations request/response example

### Vocabulary

- [speakeasy-vocabulary.yml](vocabulary/speakeasy-vocabulary.yml) — Domain vocabulary for Speakeasy platform concepts including Workspace, Organization, SDK Generation, MCP Server, and Artifact terms

## Common Properties

- [Customers](https://www.speakeasy.com/customers)
- [Documentation](https://www.speakeasy.com/docs)
- [Guide](https://www.speakeasy.com/guides)
- [Blog](https://www.speakeasy.com/blog)
- [ChangeLog](https://www.speakeasy.com/changelog)
- [About](https://www.speakeasy.com/company)
- [Contact](https://www.speakeasy.com/contact)
- [Pricing](https://www.speakeasy.com/pricing)
- [Security](https://www.speakeasy.com/legal/product-security)
- [TermsOfService](https://www.speakeasy.com/legal/terms-of-service)
- [PrivacyPolicy](https://www.speakeasy.com/legal/privacy-policy)
- [CLI](https://www.speakeasy.com/docs/speakeasy-reference/cli)
- [GitHubOrg](https://github.com/speakeasy-api)
- [Status](https://status.speakeasyapi.dev)
- [OpenAPI Hub](https://www.speakeasy.com/openapi)
- [MCP Hub](https://www.speakeasy.com/mcp)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
