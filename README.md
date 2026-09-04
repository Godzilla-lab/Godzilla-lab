# Olamilekan Busari

**AI Automation Engineer.** Production automation, AI agents, and LLM pipelines.

I build the deterministic scaffolding that makes probabilistic systems reliable enough to
run unattended. Most recently a multi-workflow n8n platform doing **5,100+ production
executions per month at a 1.6% failure rate**, and a Java/Spring Boot chatbot fleet
running across **18 Railway environments from a single Docker image**.

Nine paid client engagements delivered end to end, from requirements through deployment.
Since that work wrapped I have been building [Quorum](https://github.com/Godzilla-lab/Quorum-API),
an open-source verifiable-citation API published to npm and
[live in production](https://quorum-api-j15n.onrender.com/v1/healthz).

**Open to full-time engineering roles. Remote worldwide.**

---

## Selected work

### [Quorum](https://github.com/Godzilla-lab/Quorum-API) · Market Evidence API
`TypeScript` `Node 22` `PostgreSQL` `OpenAPI 3.1` `MCP`
[![npm](https://img.shields.io/npm/v/quorum-api.svg)](https://www.npmjs.com/package/quorum-api)

Every cited claim resolves to a stored receipt id, and a test enforces that rather than a
README asserting it. Fabricated citations are structurally impossible, not filtered out
after the fact.

14 HTTP operations against an OpenAPI 3.1 spec, a typed zero-dependency SDK, a 5-tool MCP
server over both stdio and remote HTTP, a CLI, and Standard Webhooks delivery with 75-hour
durable retry. 1,233 offline tests, exactly one runtime dependency, Apache-2.0.

Live on Render and Postgres with row-level tenancy:
```
curl https://quorum-api-j15n.onrender.com/v1/healthz
```

### [madebyhexa](https://github.com/Godzilla-lab/madebyhexa) · AI Ad Studio
`JavaScript` `Netlify Functions` `Supabase` `Stripe` `ffmpeg`

Paste a product URL and the research picks the angle before anything is generated. The
ordering is the whole product: research first, generation last.

27 Netlify functions over Supabase Postgres. A warm/cold research corpus harvests Reddit,
reviews, and the public ad library once per market and serves every later read from
memory. A Stripe credit ledger bills only cold reads and refunds idempotently. Shopify
OAuth, an ffmpeg render and stitch pipeline, 15 RLS migrations, strict CSP. 42K lines,
with pricing, prompt, and UI audits gating every ship.

### [Content Engine](https://github.com/Godzilla-lab/Blog-Automation)
`Python` `TypeScript` `Remotion` `Anthropic Claude`

One prompt produces blog posts, LinkedIn posts, X threads, and daily Instagram Reels with
voiceover, holding brand voice across all of them.

Three layers by design: Markdown SOPs hold intent, Claude orchestrates and recovers from
errors, and 18 deterministic Python scripts do the work. That split exists for a measured
reason. At 90% accuracy per step, a five-step chain succeeds 59% of the time, so anything
that can be deterministic gets pushed out of the model and into code. Automated LLM output
evaluation with 3-gate QA. 72K+ lines, active since March 2026.

### [Multi-Creator Chatbot](https://github.com/Godzilla-lab/multi-creator-chatbot)
`Java 17` `Spring Boot 4` `PostgreSQL` `Docker` `Railway`

Multi-tenant conversational platform deployed across 18 Railway production environments
from one Docker image. Re-engagement state machine, per-script performance analytics, and
isolated credentials, persona config, and analytics per tenant. Webhook ingestion, JPA
persistence, multi-stage Temurin build.

### [Lead Capture + Booking CRM](https://github.com/Godzilla-lab/lead-capture-crm)
`Next.js` `TypeScript` `Supabase`

A public form qualifies inbound by revenue band and routes qualified leads into booking;
an admin CRM runs a nine-stage Kanban pipeline over the same rows, with availability
blocking. Double-booking is prevented by a unique index at the database level, not by a
check in application code.

### [SEO Report](https://github.com/Godzilla-lab/Seo-report)
`Python`

Full-site audit tool: technical crawl, schema validation, sitemap and performance checks,
then a PDF report generator that ranks fixes by impact against effort.

---

## Stack

| | |
|---|---|
| **Automation & AI** | n8n, Make.com, Zapier, GoHighLevel, Claude API, OpenAI API, LangChain, RAG (pgvector), MCP servers, agentic workflows, LLM output evaluation |
| **Languages** | Python, TypeScript, JavaScript (Node.js), Java (Spring Boot), SQL |
| **Interfaces** | REST API design, OpenAPI 3.1, webhooks, Standard Webhooks |
| **Infrastructure** | AWS, Docker, Railway, Render, Netlify, PostgreSQL, Supabase, GitHub Actions, CI/CD |
| **CRM & Growth** | HubSpot, GoHighLevel, Pipedrive, Salesforce |

---

## Background

**AI Automation Engineer**, Hexa AI Agency · Nov 2025 to Jun 2026
**Junior AI Automation Engineer**, Automatemybiz.ai (Dubai) · Feb 2025 to Jun 2025
**AI Automation Engineer Intern**, AI2market.com (US) · Sep 2024 to Nov 2024

B.Sc. (Honours) Computer Science, Kwara State University
Oracle Generative AI Professional Certification

---

## Contact

**olamibusari607@gmail.com** · [hexaaiagency.com](https://hexaaiagency.com)
