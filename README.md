# Olamilekan Busari

Backend and full-stack engineer. I build systems that ship, mostly around applied AI:
TypeScript APIs, Python automation pipelines, and multi-tenant Spring Boot services.

Currently building **[Quorum](https://github.com/Godzilla-lab/Quorum-API)**, an evidence
API where every claim carries a receipt id that resolves back to a real stored record.
Fabricated citations are not filtered out after the fact, they fail a test before they
can ship.

I also build and run the products under [Hexa](https://github.com/Godzilla-lab/madebyhexa).

**Open to backend, full-stack, and AI engineering roles.**

---

## Selected work

### [Quorum-API](https://github.com/Godzilla-lab/Quorum-API)
`TypeScript` `Node 22` `PostgreSQL` `OpenAPI 3.1`

Market-evidence API, [published to npm](https://www.npmjs.com/package/quorum-api) under
Apache-2.0. Every returned claim is traceable to a stored record, and a test proves it
rather than a README asserting it. 1,233 tests, a full OpenAPI 3.1 spec, CI on every
push, and exactly one runtime dependency.

### [lead-capture-crm](https://github.com/Godzilla-lab/lead-capture-crm)
`TypeScript` `Supabase` `Netlify`

Two deployments backed by one database. A public lead form qualifies inbound by revenue
band and routes qualified leads straight into booking; an admin CRM runs a nine-stage
drag-and-drop pipeline over the same rows. Double-booking is prevented by a unique index
at the database level, not by a check in application code.

### [madebyhexa](https://github.com/Godzilla-lab/madebyhexa)
`JavaScript` `Supabase` `Anthropic Claude`

Paste a product link, get an ad built from that product's actual market. The ordering is
the product: research first, generation last. The expensive read runs as a background
job with status polling, because honest market research takes minutes and an HTTP request
should not pretend otherwise.

### [multi-creator-chatbot](https://github.com/Godzilla-lab/multi-creator-chatbot)
`Java 17` `Spring Boot 4` `PostgreSQL` `Docker`

Multi-tenant conversational service. One deployment serves many tenants, each with
isolated API credentials, voice configuration, content vault, and analytics. Webhook
ingestion, JPA persistence, containerised with a multi-stage Temurin build.

### [Blog-Automation](https://github.com/Godzilla-lab/Blog-Automation)
`Python` `TypeScript` `Anthropic Claude`

Content engine that turns one prompt into blog posts, Instagram carousels, Reels with
voiceover, and tweets, holding brand voice across all of them. Built on a three-layer
architecture: Markdown SOPs hold intent, an orchestration layer routes and recovers from
errors, and 18 deterministic Python scripts do the work. That split exists for a measured
reason. At 90% accuracy per step a five-step chain succeeds 59% of the time, so anything
that can be deterministic gets pushed out of the model and into code.

### [Seo-report](https://github.com/Godzilla-lab/Seo-report)
`Python`

Full-site SEO audit tool. Technical crawl, schema validation, sitemap and performance
checks, then a PDF report generator that ranks fixes by impact against effort.

---

## Stack

| | |
|---|---|
| **Languages** | TypeScript, Python, Java, JavaScript, SQL |
| **Backend** | Node.js, Spring Boot, PostgreSQL, Supabase, REST, OpenAPI 3.1 |
| **AI** | Anthropic Claude API, agent orchestration, evidence and retrieval pipelines |
| **Infra** | Docker, GitHub Actions, Railway, Netlify, Vercel |
| **Testing** | Vitest, JUnit, contract tests against an OpenAPI spec |

---

## Contact

<!-- TODO(Olamilekan): add these three lines once you have them.
     - Email you are happy to publish
     - LinkedIn URL
     - Live product links, once madebyhexa.co and the Netlify apps are back up (all 503 right now)
-->
