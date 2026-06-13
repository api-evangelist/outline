# Outline

Outline is an open-source team knowledge base and wiki with a fully featured RPC-style REST API. The API enables programmatic management of documents, collections, teams, users, groups, comments, shares, attachments, revisions, and file import/export operations. The main Outline application itself is built on the same public API.

## API Documentation

- **Developer Portal:** https://www.getoutline.com/developers
- **OpenAPI Specification:** https://raw.githubusercontent.com/outline/openapi/main/spec3.yml
- **User Guide:** https://docs.getoutline.com/s/guide

## Authentication

- **API Keys:** Create via Settings → API Keys. Authenticate with `Authorization: Bearer YOUR_API_KEY` header.
- **OAuth 2.0:** Supported for third-party application integrations with `read` and `write` scopes.

## Resources

- **Changelog:** https://www.getoutline.com/changelog
- **Status:** https://status.getoutline.com/
- **GitHub:** https://github.com/outline/outline
- **Pricing:** https://www.getoutline.com/pricing

## APIs.json Profile

This repository contains an APIs.json 0.19 profile for Outline including:

- `apis.yml` — Main APIs.json index
- `plans/outline-plans-pricing.yml` — Pricing plan details
- `rate-limits/outline-rate-limits.yml` — Rate limiting configuration
- `finops/outline-finops.yml` — Financial operations guidance
