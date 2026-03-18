# Fumadocs

Fumadocs is a modern documentation framework built on Next.js for building developer documentation sites. Website: https://fumadocs.vercel.app, GitHub: https://github.com/fuma-nama/fumadocs

## APIs

- **Fumadocs Search API** — Server-side full-text search endpoint exposed by documentation sites built with Fumadocs. Accepts query, locale, and tag parameters; returns ranked page, heading, and text results.
- **Fumadocs OpenAPI Proxy API** — HTTP proxy endpoint from the fumadocs-openapi package that forwards browser requests to external API servers for the interactive OpenAPI playground, bypassing CORS restrictions.

## Artifacts

| Type | File | Description |
|------|------|-------------|
| OpenAPI | [openapi/fumadocs-search-openapi.yml](openapi/fumadocs-search-openapi.yml) | Search API endpoint |
| OpenAPI | [openapi/fumadocs-openapi-proxy-openapi.yml](openapi/fumadocs-openapi-proxy-openapi.yml) | OpenAPI playground proxy endpoint |
| JSON Schema | [json-schema/fumadocs-page-tree-schema.json](json-schema/fumadocs-page-tree-schema.json) | Page tree navigation structure |
| JSON Schema | [json-schema/fumadocs-page-schema.json](json-schema/fumadocs-page-schema.json) | MDX page frontmatter |
| JSON Schema | [json-schema/fumadocs-meta-schema.json](json-schema/fumadocs-meta-schema.json) | Folder meta.json configuration |
| JSON Schema | [json-schema/fumadocs-search-result-schema.json](json-schema/fumadocs-search-result-schema.json) | Search result payload |
| JSON-LD | [json-ld/fumadocs-context.jsonld](json-ld/fumadocs-context.jsonld) | Linked data context for Fumadocs entities |

## Links

- [Documentation](https://fumadocs.dev/docs)
- [GitHub](https://github.com/fuma-nama/fumadocs)
- [npm: fumadocs-core](https://www.npmjs.com/package/fumadocs-core)
- [npm: fumadocs-ui](https://www.npmjs.com/package/fumadocs-ui)
- [npm: fumadocs-openapi](https://www.npmjs.com/package/fumadocs-openapi)
