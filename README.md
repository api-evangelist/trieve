# Trieve

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

Trieve (Devflow, Inc.) is an open-source, all-in-one search, recommendations, RAG, and analytics platform delivered as a REST API. The backend is written in Rust (Actix-web) and exposes endpoints for managing organizations, datasets, chunks, chunk groups, files, search, topics / messages (LLM chat), web crawls, events, analytics, and experiments. Trieve Cloud is hosted at api.trieve.ai; the same server can be self-hosted from the devflowinc/trieve repository. Official SDKs are published for TypeScript and Python.

**Areas:** Search · RAG · Vector Search · Hybrid Search · Recommendations · Analytics · Open Source

## Trieve on APIs.io

Everything profiled for Trieve is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/trieve/](https://apis.io/providers/trieve/)** — or go straight to one of the APIs or properties below.

### APIs (21)

- [Trieve REST API](https://apis.io/apis/trieve/rest-api/) — Production REST API for Trieve Cloud. Organizes resources around organizations, datasets, chunks, chunk groups, files, search, topics, messages, crawls,…
- [Trieve Chunk API](https://apis.io/apis/trieve/chunk/) — Manage chunks - the individual searchable units of content stored in a dataset - including create, update, delete, get, and bulk operations.
- [Trieve Chunk Group API](https://apis.io/apis/trieve/chunk-group/) — Group chunks into bookmark-style folders for organization, recommendations, and group-scoped search within a dataset.
- [Trieve Dataset API](https://apis.io/apis/trieve/dataset/) — Create and configure datasets that hold chunks, chunk groups, and search / RAG configuration for a workload.
- [Trieve Search API](https://apis.io/apis/trieve/search/) — Run vector, full-text, and hybrid search across a dataset, with filters, boosts, re-ranking, and highlights.
- [Trieve File API](https://apis.io/apis/trieve/file/) — Upload files (up to 1 GB), extract text, and chunk them into a dataset. Asynchronous - completion is signaled via the Events API.
- [Trieve Topic API](https://apis.io/apis/trieve/topic/) — Topics persist conversational state for generative-AI chat sessions backed by a Trieve dataset.
- [Trieve Message API](https://apis.io/apis/trieve/message/) — Messages are turns within a topic; the Message API drives RAG completions, streaming responses, and citation-aware chat against a dataset.
- [Trieve Crawl API](https://apis.io/apis/trieve/crawl/) — Create and manage web crawls that ingest pages into a dataset for search and RAG.
- [Trieve Analytics API](https://apis.io/apis/trieve/analytics/) — Query search and RAG analytics - top queries, no-result queries, latency, click-through, and experiment outcomes.
- [Trieve Events API](https://apis.io/apis/trieve/events/) — Server-sent notifications about asynchronous work such as file processing, crawl completion, and chunk ingestion.
- [Trieve Organization API](https://apis.io/apis/trieve/organization/) — Manage organizations, roles, and members.
- [Trieve Auth API](https://apis.io/apis/trieve/auth/) — Registration, login, and session handling for Trieve users.
- [Trieve TypeScript SDK](https://apis.io/apis/trieve/typescript-sdk/) — Official TypeScript / JavaScript client library for the Trieve REST API.
- [Trieve Python SDK](https://apis.io/apis/trieve/python-sdk/) — Official Python client library (trieve-py-client) for the Trieve REST API.
- [Trieve Open Source Server](https://apis.io/apis/trieve/open-source/) — Self-hostable Trieve server (Rust / Actix-web), dashboard, search and chat UIs, ingestion / file / delete workers, batch-ETL utilities, pdf2md converter,…
- [Trieve Chunk API](https://apis.io/apis/trieve/trieve-chunk-api/) — The Chunk API from Trieve — 1 operation(s) for chunk.
- [Trieve Dataset API](https://apis.io/apis/trieve/trieve-dataset-api/) — The Dataset API from Trieve — 1 operation(s) for dataset.
- [Trieve File API](https://apis.io/apis/trieve/trieve-file-api/) — The File API from Trieve — 1 operation(s) for file.
- [Trieve Message API](https://apis.io/apis/trieve/trieve-message-api/) — The Message API from Trieve — 1 operation(s) for message.
- [Trieve Topic API](https://apis.io/apis/trieve/trieve-topic-api/) — The Topic API from Trieve — 1 operation(s) for topic.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Trieve Agentic Access](https://apis.io/agentic-access/trieve/trieve-agentic-access/)

#### Collections (6)

Postman and Open Collection request collections.

- [Trieve REST API](https://apis.io/collections/trieve/open-trieve/)
- [Trieve REST Chunk API](https://apis.io/collections/trieve/open-trieve-chunk-api/)
- [Trieve REST Chunk Dataset API](https://apis.io/collections/trieve/open-trieve-dataset-api/)
- [Trieve REST Chunk File API](https://apis.io/collections/trieve/open-trieve-file-api/)
- [Trieve REST Chunk Message API](https://apis.io/collections/trieve/open-trieve-message-api/)
- [Trieve REST Chunk Topic API](https://apis.io/collections/trieve/open-trieve-topic-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Trieve — trieve rules](https://apis.io/rules/trieve/trieve-trieve-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Trieve Authentication](https://apis.io/security/trieve/trieve-authentication/)
- [Trieve Domain Security](https://apis.io/security/trieve/trieve-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Trieve Plans Pricing](https://apis.io/plans/trieve/trieve-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Trieve Rate Limits](https://apis.io/rate-limits/trieve/trieve-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Trieve Finops](https://apis.io/finops/trieve/trieve-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://trieve.ai/)
- [Documentation](https://docs.trieve.ai/)
- [Pricing](https://trieve.ai/pricing)
- [Blog](https://trieve.ai/blog)

## API Evangelist rating

**Kin Score 40.2** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 47.6 |
| Contract governance | 15.2 |
| Operational transparency | 36.8 |
| Developer ergonomics | 22.6 |
| Access clarity | 10.5 |

**Agent readiness 17.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 11.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/trieve/](https://apis.io/providers/trieve/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Trieve: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/trieve/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
