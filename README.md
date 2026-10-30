# MediaRuntime

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

MediaRuntime is an asynchronous media-processing API and hosted sticker runtime for server-side applications, served at https://mediaruntime.com/v1. It publishes two products in its apis.json. The Media API takes video, audio and image jobs (POST /v1/jobs) and returns canonical ZIP bundles through polling or signed terminal webhooks, with presets and account-scoped recipes, moderation verdicts, analysis reports, upload targets and watermarks. The Stickers API configures sticker collections, discovers enabled Hosted Packs, searches stable sticker metadata and resolves short-lived approved asset URLs. The OpenAPI 3.1 contract at https://mediaruntime.com/openapi.json describes 33 paths and 41 operations. Server requests authenticate with an X-API-Key workspace key, and a public sandbox session is available. Official tools are the @mediaruntime/node SDK and @mediaruntime/cli on npm, the mediaruntime Python SDK on PyPI, and a GitHub quickstarts repository.

**Areas:** Media Processing · Video · Audio · Runtime · Video Encoding · Audio Processing · Image Processing · Content Moderation · Media API · Asynchronous Processing

## MediaRuntime on APIs.io

Everything profiled for MediaRuntime is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/mediaruntime/](https://apis.io/providers/mediaruntime/)** — or go straight to one of the APIs or properties below.

### APIs (16)

- [MediaRuntime Media API](https://apis.io/apis/mediaruntime/media-api/) — Submit asynchronous video, audio, and image jobs and receive canonical ZIP bundles through polling or signed terminal webhooks. One of the two products in…
- [MediaRuntime Stickers API](https://apis.io/apis/mediaruntime/stickers-api/) — Configure sticker collections, discover enabled Hosted Packs, search stable sticker metadata, and resolve approved short-lived asset delivery URLs. One of…
- [MediaRuntime Discovery API](https://apis.io/apis/mediaruntime/mediaruntime-discovery-api/) — Public capability and contract discovery.
- [MediaRuntime Job Results API](https://apis.io/apis/mediaruntime/mediaruntime-job-results-api/) — Redeem completed job output bundles.
- [MediaRuntime Jobs API](https://apis.io/apis/mediaruntime/mediaruntime-jobs-api/) — Create, list, and inspect asynchronous media jobs.
- [MediaRuntime Media Analysis API](https://apis.io/apis/mediaruntime/mediaruntime-media-analysis-api/) — Read analysis reports produced by requested presets.
- [MediaRuntime API](https://apis.io/apis/mediaruntime/mediaruntime-mediaruntime-api-api/) — The four signed terminal webhook events MediaRuntime posts to an account's endpoint (job.completed, job.failed, job.partial, job.rejected); this document…
- [MediaRuntime Moderation API](https://apis.io/apis/mediaruntime/mediaruntime-moderation-api/) — Read a job's requested moderation verdict.
- [MediaRuntime Recipes API](https://apis.io/apis/mediaruntime/mediaruntime-recipes-api/) — Manage immutable, account-scoped processing recipes.
- [MediaRuntime Sandbox API](https://apis.io/apis/mediaruntime/mediaruntime-sandbox-api/) — Create a bounded public-sandbox session.
- [MediaRuntime Uploads API](https://apis.io/apis/mediaruntime/mediaruntime-uploads-api/) — Optional upload targets for local media bytes.
- [MediaRuntime Watermarks API](https://apis.io/apis/mediaruntime/mediaruntime-watermarks-api/) — Configure the account watermark logo.
- [MediaRuntime Webhooks API](https://apis.io/apis/mediaruntime/mediaruntime-webhooks-api/) — Retry delivery of signed terminal events.
- [MediaRuntime Marketplace API](https://apis.io/apis/mediaruntime/mediaruntime-marketplace-api/) — Browse MediaRuntime character packs and their public previews.
- [MediaRuntime Sticker Collections API](https://apis.io/apis/mediaruntime/mediaruntime-sticker-collections-api/) — Configure which activated character packs each application exposes.
- [MediaRuntime Sticker Runtime API](https://apis.io/apis/mediaruntime/mediaruntime-sticker-runtime-api/) — Search, inspect, and resolve collection-scoped hosted stickers.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Mediaruntime Webhooks](https://apis.io/asyncapis/mediaruntime/mediaruntime-webhooks/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Mediaruntime Agentic Access](https://apis.io/agentic-access/mediaruntime/mediaruntime-agentic-access/)

#### JSON Schema (19)

The data models the API reads and writes.

- [ArchivedRecipeResponse](https://apis.io/schemas/mediaruntime/mediaruntime-archived-recipe-response/)
- [CapabilitiesResponse](https://apis.io/schemas/mediaruntime/mediaruntime-capabilities-response/)
- [CreateJobRequest](https://apis.io/schemas/mediaruntime/mediaruntime-create-job-request/)
- [HostedRecipeListResponse](https://apis.io/schemas/mediaruntime/mediaruntime-hosted-recipe-list-response/)
- [HostedRecipeResponse](https://apis.io/schemas/mediaruntime/mediaruntime-hosted-recipe-response/)
- [JobListResponse](https://apis.io/schemas/mediaruntime/mediaruntime-job-list-response/)
- [JobModerationInfo](https://apis.io/schemas/mediaruntime/mediaruntime-job-moderation-info/)
- [JobReportResponse](https://apis.io/schemas/mediaruntime/mediaruntime-job-report-response/)
- [JobResponse](https://apis.io/schemas/mediaruntime/mediaruntime-job-response/)
- [JobStatusResponse](https://apis.io/schemas/mediaruntime/mediaruntime-job-status-response/)
- [RecipeCreateRequest](https://apis.io/schemas/mediaruntime/mediaruntime-recipe-create-request/)
- [RecipeVersionCreateRequest](https://apis.io/schemas/mediaruntime/mediaruntime-recipe-version-create-request/)
- [SandboxSessionResponse](https://apis.io/schemas/mediaruntime/mediaruntime-sandbox-session-response/)
- [UploadUrlRequest](https://apis.io/schemas/mediaruntime/mediaruntime-upload-url-request/)
- [UploadUrlResponse](https://apis.io/schemas/mediaruntime/mediaruntime-upload-url-response/)
- [WatermarkLogoConfirmRequest](https://apis.io/schemas/mediaruntime/mediaruntime-watermark-logo-confirm-request/)
- [WatermarkLogoResponse](https://apis.io/schemas/mediaruntime/mediaruntime-watermark-logo-response/)
- [WatermarkLogoUploadUrlRequest](https://apis.io/schemas/mediaruntime/mediaruntime-watermark-logo-upload-url-request/)
- [WebhookRetryResponse](https://apis.io/schemas/mediaruntime/mediaruntime-webhook-retry-response/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Mediaruntime Context](https://apis.io/jsonld/mediaruntime/mediaruntime-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [MediaRuntime API Rules](https://apis.io/rules/mediaruntime/mediaruntime-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Mediaruntime Authentication](https://apis.io/security/mediaruntime/mediaruntime-authentication/)
- [Mediaruntime Domain Security](https://apis.io/security/mediaruntime/mediaruntime-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Mediaruntime Plans Pricing](https://apis.io/plans/mediaruntime/mediaruntime-plans-pricing/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://mediaruntime.com)
- [Documentation](https://mediaruntime.com/en/docs)
- [Getting started](https://mediaruntime.com/docs#quickstart)
- [API reference](https://mediaruntime.com/en/docs/)
- [Pricing](https://mediaruntime.com/en/pricing/)
- [Sign up](https://mediaruntime.com/account?signup=1)
- [Support](https://mediaruntime.com/contact)
- [Blog](https://mediaruntime.com/blog)
- [Terms of service](https://mediaruntime.com/legal#terms)
- [Privacy policy](https://mediaruntime.com/legal#privacy)
- [GitHub](https://github.com/ericel)

## API Evangelist rating

**Kin Score 63.5** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 64.3 |
| Contract quality | 75.1 |
| Contract governance | 22.0 |
| Operational transparency | 13.2 |
| Developer ergonomics | 89.9 |
| Access clarity | 76.3 |

**Agent readiness 39.6** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 24.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/mediaruntime/](https://apis.io/providers/mediaruntime/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for MediaRuntime: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/mediaruntime/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
