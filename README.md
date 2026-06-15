# Trieve (trieve)

Trieve (Devflow, Inc.) is an open-source, all-in-one search, recommendations, RAG, and analytics platform delivered as a REST API. The backend is written in Rust (Actix-web) and exposes endpoints for managing organizations, datasets, chunks, chunk groups, files, search, topics / messages (LLM chat), web crawls, events, analytics, and experiments. Trieve Cloud is hosted at api.trieve.ai; the same server can be self-hosted from the devflowinc/trieve repository. Official SDKs are published for TypeScript and Python.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/trieve/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/trieve/refs/heads/main/apis.yml)

## Tags

- Search
- RAG
- Vector Search
- Hybrid Search
- Recommendations
- Analytics
- Open Source

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Trieve REST API

Production REST API for Trieve Cloud. Organizes resources around organizations, datasets, chunks, chunk groups, files, search, topics, messages, crawls, analytics, events, experiments, and billing. Documented with OpenAPI and rendered via Redoc.

- **Human URL:** [https://docs.trieve.ai/api-reference](https://docs.trieve.ai/api-reference)
- **Base URL:** `https://api.trieve.ai`

#### Tags

- REST
- OpenAPI

#### Properties

- [Documentation](https://docs.trieve.ai/api-reference)
- [Redoc](https://api.trieve.ai/redoc)
- [Postman Collection](collections/trieve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trieve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trieve Chunk API

Manage chunks - the individual searchable units of content stored in a dataset - including create, update, delete, get, and bulk operations.

- **Human URL:** [https://docs.trieve.ai/api-reference](https://docs.trieve.ai/api-reference)
- **Base URL:** `https://api.trieve.ai`

#### Tags

- Chunks
- Content

#### Properties

- [Documentation](https://docs.trieve.ai/api-reference)
- [Postman Collection](collections/trieve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trieve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trieve Chunk Group API

Group chunks into bookmark-style folders for organization, recommendations, and group-scoped search within a dataset.

- **Human URL:** [https://docs.trieve.ai/api-reference](https://docs.trieve.ai/api-reference)
- **Base URL:** `https://api.trieve.ai`

#### Tags

- Groups
- Organization

#### Properties

- [Documentation](https://docs.trieve.ai/api-reference)
- [Postman Collection](collections/trieve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trieve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trieve Dataset API

Create and configure datasets that hold chunks, chunk groups, and search / RAG configuration for a workload.

- **Human URL:** [https://docs.trieve.ai/api-reference](https://docs.trieve.ai/api-reference)
- **Base URL:** `https://api.trieve.ai`

#### Tags

- Datasets
- Configuration

#### Properties

- [Documentation](https://docs.trieve.ai/api-reference)
- [Postman Collection](collections/trieve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trieve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trieve Search API

Run vector, full-text, and hybrid search across a dataset, with filters, boosts, re-ranking, and highlights.

- **Human URL:** [https://docs.trieve.ai/api-reference](https://docs.trieve.ai/api-reference)
- **Base URL:** `https://api.trieve.ai`

#### Tags

- Search
- Hybrid
- Vector
- Full-Text

#### Properties

- [Documentation](https://docs.trieve.ai/api-reference)
- [Postman Collection](collections/trieve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trieve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trieve File API

Upload files (up to 1 GB), extract text, and chunk them into a dataset. Asynchronous - completion is signaled via the Events API.

- **Human URL:** [https://docs.trieve.ai/api-reference](https://docs.trieve.ai/api-reference)
- **Base URL:** `https://api.trieve.ai`

#### Tags

- Files
- Ingestion

#### Properties

- [Documentation](https://docs.trieve.ai/api-reference)
- [Postman Collection](collections/trieve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trieve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trieve Topic API

Topics persist conversational state for generative-AI chat sessions backed by a Trieve dataset.

- **Human URL:** [https://docs.trieve.ai/api-reference](https://docs.trieve.ai/api-reference)
- **Base URL:** `https://api.trieve.ai`

#### Tags

- Topics
- Chat
- RAG

#### Properties

- [Documentation](https://docs.trieve.ai/api-reference)
- [Postman Collection](collections/trieve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trieve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trieve Message API

Messages are turns within a topic; the Message API drives RAG completions, streaming responses, and citation-aware chat against a dataset.

- **Human URL:** [https://docs.trieve.ai/api-reference](https://docs.trieve.ai/api-reference)
- **Base URL:** `https://api.trieve.ai`

#### Tags

- Messages
- RAG
- Streaming

#### Properties

- [Documentation](https://docs.trieve.ai/api-reference)
- [Postman Collection](collections/trieve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trieve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trieve Crawl API

Create and manage web crawls that ingest pages into a dataset for search and RAG.

- **Human URL:** [https://docs.trieve.ai/api-reference](https://docs.trieve.ai/api-reference)
- **Base URL:** `https://api.trieve.ai`

#### Tags

- Crawl
- Ingestion

#### Properties

- [Documentation](https://docs.trieve.ai/api-reference)
- [Postman Collection](collections/trieve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trieve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trieve Analytics API

Query search and RAG analytics - top queries, no-result queries, latency, click-through, and experiment outcomes.

- **Human URL:** [https://docs.trieve.ai/api-reference](https://docs.trieve.ai/api-reference)
- **Base URL:** `https://api.trieve.ai`

#### Tags

- Analytics
- Search Analytics

#### Properties

- [Documentation](https://docs.trieve.ai/api-reference)
- [Postman Collection](collections/trieve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trieve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trieve Events API

Server-sent notifications about asynchronous work such as file processing, crawl completion, and chunk ingestion.

- **Human URL:** [https://docs.trieve.ai/api-reference](https://docs.trieve.ai/api-reference)
- **Base URL:** `https://api.trieve.ai`

#### Tags

- Events
- Webhooks
- Async

#### Properties

- [Documentation](https://docs.trieve.ai/api-reference)
- [Postman Collection](collections/trieve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trieve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trieve Organization API

Manage organizations, roles, and members.

- **Human URL:** [https://docs.trieve.ai/api-reference](https://docs.trieve.ai/api-reference)
- **Base URL:** `https://api.trieve.ai`

#### Tags

- Organization
- Admin

#### Properties

- [Documentation](https://docs.trieve.ai/api-reference)
- [Postman Collection](collections/trieve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trieve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trieve Auth API

Registration, login, and session handling for Trieve users.

- **Human URL:** [https://docs.trieve.ai/api-reference](https://docs.trieve.ai/api-reference)
- **Base URL:** `https://api.trieve.ai`

#### Tags

- Auth
- Identity

#### Properties

- [Documentation](https://docs.trieve.ai/api-reference)
- [Postman Collection](collections/trieve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trieve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trieve TypeScript SDK

Official TypeScript / JavaScript client library for the Trieve REST API.

- **Human URL:** [https://ts-sdk.trieve.ai](https://ts-sdk.trieve.ai)
- **Base URL:** `https://github.com/devflowinc/trieve`

#### Tags

- SDK
- TypeScript
- JavaScript

#### Properties

- [Documentation](https://ts-sdk.trieve.ai)
- [Repository](https://github.com/devflowinc/trieve)
- [Postman Collection](collections/trieve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trieve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trieve Python SDK

Official Python client library (trieve-py-client) for the Trieve REST API.

- **Human URL:** [https://pypi.org/project/trieve-py-client/](https://pypi.org/project/trieve-py-client/)
- **Base URL:** `https://github.com/devflowinc/trieve`

#### Tags

- SDK
- Python

#### Properties

- [Documentation](https://pypi.org/project/trieve-py-client/)
- [Repository](https://github.com/devflowinc/trieve)
- [Postman Collection](collections/trieve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trieve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trieve Open Source Server

Self-hostable Trieve server (Rust / Actix-web), dashboard, search and chat UIs, ingestion / file / delete workers, batch-ETL utilities, pdf2md converter, and Helm charts for Kubernetes deployment.

- **Human URL:** [https://github.com/devflowinc/trieve](https://github.com/devflowinc/trieve)
- **Base URL:** `https://github.com/devflowinc/trieve`

#### Tags

- Open Source
- Self-Hosted
- Rust

#### Properties

- [Repository](https://github.com/devflowinc/trieve)
- [Postman Collection](collections/trieve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trieve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://trieve.ai/)
- [Documentation](https://docs.trieve.ai/)
- [Git Hub](https://github.com/devflowinc)
- [Pricing](https://trieve.ai/pricing)
- [Blog](https://trieve.ai/blog)
- [L L Ms Txt](https://docs.trieve.ai/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
