# LlamaParse (llamaparse)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

LlamaParse is an enterprise document parsing and AI pipeline platform from LlamaIndex that converts complex PDFs, Office files, and 130+ document formats into LLM-ready structured outputs. The platform offers six composable products under a single API key: Parse (agentic OCR), Extract (structured data extraction), Classify, Split, Sheets, and Index. Developers access the platform through Python and TypeScript SDKs or directly via the LlamaCloud REST API, with EU-region hosting available.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/llamaparse/refs/heads/main/apis.yml

**Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=llamaparse-api-evangelist&utm_content=repo

---

## Tags

Document Parsing, OCR, PDF, LLM, RAG, AI, Document Intelligence, Structured Data Extraction

---

## APIs

| API | Description | Docs |
|-----|-------------|------|
| LlamaParse Parse API | Core agentic OCR and document parsing API with tier-based processing (fast, cost-effective, agentic, agentic-plus) | [Docs](https://developers.llamaindex.ai/llamaparse/parse/) |
| LlamaParse Extract API | Structured JSON data extraction from unstructured documents using developer-defined schemas | [Docs](https://developers.llamaindex.ai/llamaparse/) |
| LlamaParse Classify API | Document classification in fast or multimodal modes for pre-filtering workflows | [Docs](https://developers.llamaindex.ai/llamaparse/) |
| LlamaCloud Index API | Managed vector index API for ingesting parsed documents into searchable LlamaCloud indexes | [Docs](https://developers.llamaindex.ai/llamaparse/) |

---

## Plans, Rate Limits, and FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/llamaparse-plans-pricing.yml](plans/llamaparse-plans-pricing.yml) |
| Rate Limits | [rate-limits/llamaparse-rate-limits.yml](rate-limits/llamaparse-rate-limits.yml) |
| FinOps | [finops/llamaparse-finops.yml](finops/llamaparse-finops.yml) |

**Pricing summary:** Free (10,000 credits/mo), Starter ($50/mo, 40,000 credits), Pro ($500/mo, 400,000 credits), Enterprise (custom). Credits cost $1.25 per 1,000. Parse tiers range from 1 credit/page (fast) to 45 credits/page (agentic-plus).

**Rate limits:** 50 QPS on file upload (per project, 5s window), 50 QPS on parse upload (per org, 10s window), 40 QPS on classify (per org, 1s window). Free tier: 20 requests/minute globally. HTTP 429 returned on breach.

---

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

---

## Common Properties

| Property | URL |
|----------|-----|
| Website | https://www.llamaindex.ai/ |
| Developer Documentation | https://developers.llamaindex.ai/llamaparse/ |
| API Reference | https://developers.llamaindex.ai/llamaparse/parse/guides/api-reference/ |
| GitHub Organization | https://github.com/run-llama |
| Python SDK (PyPI) | https://pypi.org/project/llama-cloud/ |
| TypeScript SDK (npm) | https://www.npmjs.com/package/@llamaindex/llama-cloud |
| LinkedIn | https://www.linkedin.com/company/llamaindex |
| X / Twitter | https://twitter.com/llama_index |
| Blog | https://www.llamaindex.ai/blog |
| Changelog | https://developers.llamaindex.ai/python/framework/changelog/ |
| Pricing | https://www.llamaindex.ai/pricing |
| Status Page | https://llamaindex.statuspage.io/ |

---

## Maintainers

**Kin Lane** — kin@apievangelist.com
