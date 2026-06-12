# LlamaParse (llamaparse)

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
