# Statshawk

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

Statshawk provides sports statistics via a REST API and an MCP for AI assistants. It offers comprehensive data on leagues, teams, and players, enabling developers to integrate real-time scores, schedules, and analytics into applications. The platform supports self‑serve API keys, detailed documentation, and a hosted MCP for Claude, ChatGPT, and other LLMs, with a single billing account and flexible pricing.

**Areas:** Company · Sports · Statistics · API · MCP · AI

## Statshawk on APIs.io

Everything profiled for Statshawk is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/statshawk-ai/](https://apis.io/providers/statshawk-ai/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Statshawk Account API](https://apis.io/apis/statshawk-ai/statshawk-ai-account-api/) — Authenticated account reads. `GET /v1/account/usage` reports plan, period usage, remaining units, reset time, and analysis access. Unmetered by design so…
- [Statshawk Analysis API](https://apis.io/apis/statshawk-ai/statshawk-ai-analysis-api/) — Composite analysis reads: a person-keyed player-prop card (per-game values, average, over-rate), a slate stat board, and a side-by-side team comparison.…
- [Statshawk Assets API](https://apis.io/apis/statshawk-ai/statshawk-ai-assets-api/) — Static asset proxy for team logo PNGs with long-lived cache headers; suitable for direct embedding in client apps.
- [Statshawk Competitions API](https://apis.io/apis/statshawk-ai/statshawk-ai-competitions-api/) — Competitions and their editions, edition participants / games / standings, and per-competition capability discovery. Replaces the old league lens.
- [Statshawk Contests API](https://apis.io/apis/statshawk-ai/statshawk-ai-contests-api/) — Contest detail (the team-Match home/away/score view) and the person-keyed boxscore — one typed per-phase stat line per appearance, with a `finalized` flag.
- [Statshawk Persons API](https://apis.io/apis/statshawk-ai/statshawk-ai-persons-api/) — Person profile, appearances, game log, team memberships, materialized season stats, per-person capability discovery (which phases/measures a person actually…
- [Statshawk Teams API](https://apis.io/apis/statshawk-ai/statshawk-ai-teams-api/) — Team profile, as-of roster (reconstructed from appearance facts), games, game log, and materialized season stats. A national side is just a team with a…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Statshawk Agentic Access](https://apis.io/agentic-access/statshawk-ai/statshawk-ai-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [ApiResponseContestDetailList](https://apis.io/schemas/statshawk-ai/statshawk-ai-api-response-contest-detail-list/)
- [ApiResponsePersonGameLogList](https://apis.io/schemas/statshawk-ai/statshawk-ai-api-response-person-game-log-list/)
- [ApiResponseStandingsEntryList](https://apis.io/schemas/statshawk-ai/statshawk-ai-api-response-standings-entry-list/)
- [PublicStatResponseFixtureAudit](https://apis.io/schemas/statshawk-ai/statshawk-ai-public-stat-response-fixture-audit/)
- [PublicStatResponseStatDetail](https://apis.io/schemas/statshawk-ai/statshawk-ai-public-stat-response-stat-detail/)
- [PublicStatResponseStatHistoryPage](https://apis.io/schemas/statshawk-ai/statshawk-ai-public-stat-response-stat-history-page/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Statshawk Ai Context](https://apis.io/jsonld/statshawk-ai/statshawk-ai-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Statshawk API Rules](https://apis.io/rules/statshawk-ai/statshawk-ai-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Statshawk Authentication](https://apis.io/security/statshawk-ai/statshawk-ai-authentication/)
- [Statshawk Domain Security](https://apis.io/security/statshawk-ai/statshawk-ai-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Statshawk Plans Pricing](https://apis.io/plans/statshawk-ai/statshawk-ai-plans-pricing/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.statshawk.ai/)
- [Documentation](https://www.statshawk.ai/docs)
- [API reference](https://www.statshawk.ai/docs/reference)
- [Pricing](https://www.statshawk.ai/pricing)
- [Changelog](https://www.statshawk.ai/docs/whats-new)
- [Terms of service](https://www.statshawk.ai/terms)
- [Privacy policy](https://www.statshawk.ai/privacy)

## API Evangelist rating

**Kin Score 57.8** — strong · rubric 0.27.0 · scored 2026-11-26

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 60.9 |
| Contract governance | 79.1 |
| Operational transparency | 23.7 |
| Developer ergonomics | 38.1 |
| Access clarity | 73.2 |

**Agent readiness 55.9** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | verified |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 22.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/statshawk-ai/](https://apis.io/providers/statshawk-ai/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Statshawk: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/statshawk-ai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
