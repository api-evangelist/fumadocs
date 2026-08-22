# Fumadocs (fumadocs)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
