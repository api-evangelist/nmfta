# NMFTA

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

The National Motor Freight Traffic Association (NMFTA) is the nonprofit membership body that has set the standards for North American freight since 1956, and through its Digital Standards Development Council (DSDC) it publishes that industry agreement as open OpenAPI contracts. Two councils sit under the DSDC — the Digital LTL Council, founded November 2020, and the Digital FTL Council, which absorbed the Scheduling Standards Consortium — and between them they turn the paper artifacts of trucking into machine-readable APIs: the electronic bill of lading, the rate quote, the invoice and supporting documents, in-transit visibility, appointment scheduling, book and tender, and preliminary freight charges. For most of NMFTA's history its standards were classification and coding — the NMFC freight classification, ClassIT+, SCAC carrier codes, SPLC location codes — and the DSDC is the same institution doing the same job for the API layer. It is one of the clearest examples of an old, mandate-free trade association choosing specifications-as-code over another PDF behind a membership wall, and the gap between what its website advertises as released and what its public repositories actually contain is the most interesting thing about it.

**Areas:** API Standards · DSDC · Digital FTL Council · Digital LTL Council · Freight · Full Truckload · LTL · Logistics · NMFTA · OpenAPI · Standards · Standards Body

## NMFTA on APIs.io

Everything profiled for NMFTA is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/nmfta/](https://apis.io/providers/nmfta/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [NMFTA Carrier API Standards API](https://apis.io/apis/nmfta/nmfta-carrier-api-standards-api/) — Standards for Carrier APIs
- [NMFTA Document Management API](https://apis.io/apis/nmfta/nmfta-document-management-api/) — Endpoints for uploading, and managing supporting documents.
- [NMFTA Events API](https://apis.io/apis/nmfta/nmfta-events-api/) — Pull shipment events
- [NMFTA In Transit Visibility API](https://apis.io/apis/nmfta/nmfta-in-transit-visibility-api-api/) — The In Transit Visibility API API from NMFTA — 0 operation(s) for in transit visibility api.
- [NMFTA Invoice Management API](https://apis.io/apis/nmfta/nmfta-invoice-management-api/) — Endpoints for creating, retrieving, and managing invoices.
- [NMFTA Preliminary Freight Charges API](https://apis.io/apis/nmfta/nmfta-preliminary-freight-charges-api/) — Access freight charges information
- [NMFTA Rate Quote API Standards API](https://apis.io/apis/nmfta/nmfta-rate-quote-api-standards-api/) — Standards for the FTL Rate Quote API
- [NMFTA Subscriptions API](https://apis.io/apis/nmfta/nmfta-subscriptions-api/) — Manage webhook subscriptions
- [NMFTA Webhooks API](https://apis.io/apis/nmfta/nmfta-webhooks-api/) — Webhook management and testing

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Collections (6)

Postman and Open Collection request collections.

- [Electronic Bill Of Lading API](https://apis.io/collections/nmfta/open-nmfta-dsdc-ftl-ebol/)
- [In-Transit Visibility API](https://apis.io/collections/nmfta/open-nmfta-dsdc-ftl-in-transit-visibility/)
- [Invoice & Document API](https://apis.io/collections/nmfta/open-nmfta-dsdc-ftl-invoice-and-documents/)
- [Rate Quote API](https://apis.io/collections/nmfta/open-nmfta-dsdc-ftl-rate-quote/)
- [Electronic Bill Of Lading Service](https://apis.io/collections/nmfta/open-nmfta-dsdc-ltl-ebol-2.1/)
- [Preliminary Freight Charges (PFC) API](https://apis.io/collections/nmfta/open-nmfta-dsdc-ltl-preliminary-freight-charges/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.nmfta.org/)
- [Blog](https://nmfta.org/news-resources/blog/)
- [GitHub](https://github.com/dsdcapis)

## API Evangelist rating

**Kin Score 18.9** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 63.4 |
| Contract quality | 43.8 |
| Contract governance | 0.0 |
| Operational transparency | 2.6 |
| Developer ergonomics | 21.4 |
| Access clarity | 0.0 |

**Agent readiness 17.3** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 0.0** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/nmfta/](https://apis.io/providers/nmfta/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for NMFTA: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/nmfta/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
