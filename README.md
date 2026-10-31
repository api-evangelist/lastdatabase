# LastDatabase

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

LastDatabase is a B2B and consumer contact-data marketplace selling email, phone and fax lead lists organised by country, industry, category and job title, plus data enrichment and email verification. Developers reach it two ways: the Lead Search API, a single Bearer-key REST endpoint (GET /api/leads/search) filterable by type, country, city, industry, keyword and limit, sold on Free, Pro and Enterprise daily-request plans; and an OAuth-protected remote MCP server at lastdatabase.com/mcp exposing search_people, unlock_people, verify_email and get_credits tools gated by scopes. It publishes an OpenAPI 3.1 document, an llms.txt, a public Postman collection and a Trust Center claiming ISO/IEC 27001.

**Areas:** Contact Data · Lead Generation · B2B Data · Email Verification · Data Enrichment · Sales Prospecting · MCP

## LastDatabase on APIs.io

Everything profiled for LastDatabase is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/lastdatabase/](https://apis.io/providers/lastdatabase/)** — or go straight to one of the APIs or properties below.

### APIs (2)

- [LastDatabase MCP Server](https://apis.io/apis/lastdatabase/mcp-server/) — OAuth-protected remote Model Context Protocol server at https://lastdatabase.com/mcp exposing four scope-gated tools: search_people (non-charging masked B2B…
- [LastDatabase Leads API](https://apis.io/apis/lastdatabase/lastdatabase-leads-api/) — Search supported LastDatabase lead inventory.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [LastDatabase MCP Server](https://apis.io/servers/lastdatabase/lastdatabase-mcp-server/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Lastdatabase Agentic Access](https://apis.io/agentic-access/lastdatabase/lastdatabase-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [LeadSearchResponse](https://apis.io/schemas/lastdatabase/lastdatabase-lead-search-response/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Lastdatabase Context](https://apis.io/jsonld/lastdatabase/lastdatabase-context/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Lastdatabase Lead Search Overlay](https://apis.io/overlays/lastdatabase/lastdatabase-lead-search-overlay/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [LastDatabase API Rules](https://apis.io/rules/lastdatabase/lastdatabase-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Lastdatabase Authentication](https://apis.io/security/lastdatabase/lastdatabase-authentication/)
- [Lastdatabase Domain Security](https://apis.io/security/lastdatabase/lastdatabase-domain-security/)
- [Lastdatabase Trust Center](https://apis.io/security/lastdatabase/lastdatabase-trust-center/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Lastdatabase Scopes](https://apis.io/scopes/lastdatabase/lastdatabase-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Lastdatabase Plans Pricing](https://apis.io/plans/lastdatabase/lastdatabase-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Lastdatabase Rate Limits](https://apis.io/rate-limits/lastdatabase/lastdatabase-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://lastdatabase.com/)
- [Documentation](https://lastdatabase.com/docs)
- [Getting started](https://lastdatabase.com/docs/getting-started)
- [Pricing](https://lastdatabase.com/pricing)
- [Sign up](https://lastdatabase.com/register)
- [Support](https://lastdatabase.com/contact)
- [Blog](https://lastdatabase.com/blog)
- [Compliance](https://lastdatabase.com/trust-center)
- [Terms of service](https://lastdatabase.com/terms)
- [Privacy policy](https://lastdatabase.com/privacy)

## API Evangelist rating

**Kin Score 66.9** — exemplar · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 66.9 |
| Contract governance | 35.6 |
| Operational transparency | 31.6 |
| Developer ergonomics | 61.2 |
| Access clarity | 92.1 |

**Agent readiness 58.6** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | na |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | unknown |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | na |

**Regulatory alignment 39.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/lastdatabase/](https://apis.io/providers/lastdatabase/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for LastDatabase: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/lastdatabase/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
