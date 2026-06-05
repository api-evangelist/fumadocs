# Fumadocs (fumadocs)

Fumadocs is a modern documentation framework built on Next.js for building developer documentation sites. It provides a complete set of composable packages for content loading, navigation tree generation, full-text search, UI components, and interactive API reference generation from OpenAPI specifications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fumadocs/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fumadocs/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Documentation
- Framework
- Next.js
- React

## Timestamps

- **Created:** 2026-03-18
- **Modified:** 2026-05-19

## APIs

### Fumadocs

Fumadocs is an open-source documentation framework built on Next.js and React for creating fast, modern developer documentation sites. It provides a full stack of composable packages including fumadocs-core for source loading, page tree generation, and search; fumadocs-ui for pre-built accessible React components, themes, and layouts; fumadocs-openapi for generating interactive API reference pages from OpenAPI specifications with a built-in playground; and a CLI for scaffolding new projects.

- **Human URL:** [https://fumadocs.dev](https://fumadocs.dev)

#### Tags

- Documentation
- Framework
- Next.js

#### Properties

- [Documentation](https://fumadocs.dev/docs)
- [Git Hub](https://github.com/fuma-nama/fumadocs)
- [Postman Collection](collections/fumadocs-openapi-proxy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fumadocs-openapi-proxy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/fumadocs-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fumadocs-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fumadocs Search API

The Fumadocs Search API is a server-side HTTP endpoint embedded in each Fumadocs documentation site that enables full-text search across all indexed documentation content. The endpoint (typically at /api/search) accepts a query string along with optional locale and tag filters, and returns a ranked list of matching pages, headings, and text segments with highlighted content and breadcrumb trails.

- **Human URL:** [https://fumadocs.dev/docs/headless/search/orama](https://fumadocs.dev/docs/headless/search/orama)

#### Tags

- Documentation
- Search

#### Properties

- [Documentation](https://fumadocs.dev/docs/headless/search/orama)
- [OpenAPI](openapi/fumadocs-search-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fumadocs-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fumadocs-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/fumadocs-search-result-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Fumadocs OpenAPI Proxy API

The Fumadocs OpenAPI Proxy API is a server-side HTTP proxy included in the fumadocs-openapi package that enables the interactive API playground to make authenticated requests to external API servers from the browser without CORS restrictions. Documentation sites mount the proxy at a route such as /api/proxy, where it accepts any HTTP method, extracts the target URL from the url query parameter, and transparently forwards the request to the upstream server.

- **Human URL:** [https://fumadocs.dev/docs/ui/openapi](https://fumadocs.dev/docs/ui/openapi)

#### Tags

- Documentation
- OpenAPI
- Proxy

#### Properties

- [Documentation](https://fumadocs.dev/docs/ui/openapi)
- [OpenAPI](openapi/fumadocs-openapi-proxy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fumadocs-openapi-proxy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fumadocs-openapi-proxy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://fumadocs.dev)
- [Documentation](https://fumadocs.dev/docs)
- [Git Hub](https://github.com/fuma-nama/fumadocs)
- [Documentation](https://fumadocs.dev/docs/ui/components)
- [Documentation](https://fumadocs.dev/docs/headless/search/orama)
- [Documentation](https://fumadocs.dev/docs/ui/openapi)
- [Distribution](https://www.npmjs.com/package/fumadocs-core)
- [Distribution](https://www.npmjs.com/package/fumadocs-ui)
- [Distribution](https://www.npmjs.com/package/fumadocs-openapi)
- [License](https://github.com/fuma-nama/fumadocs/blob/main/LICENSE)
- [JSON Schema](json-schema/fumadocs-page-tree-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/fumadocs-page-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/fumadocs-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/fumadocs-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
