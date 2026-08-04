# NMFTA (nmfta)

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

The National Motor Freight Traffic Association (NMFTA) is the nonprofit membership body that has set the standards for North American freight since 1956, and through its Digital Standards Development Council (DSDC) it publishes that industry agreement as open OpenAPI contracts. Two councils sit under the DSDC — the Digital LTL Council, founded November 2020, and the Digital FTL Council, which absorbed the Scheduling Standards Consortium — and between them they turn the paper artifacts of trucking into machine-readable APIs: the electronic bill of lading, the rate quote, the invoice and supporting documents, in-transit visibility, appointment scheduling, book and tender, and preliminary freight charges. For most of NMFTA's history its standards were classification and coding — the NMFC freight classification, ClassIT+, SCAC carrier codes, SPLC location codes — and the DSDC is the same institution doing the same job for the API layer. It is one of the clearest examples of an old, mandate-free trade association choosing specifications-as-code over another PDF behind a membership wall, and the gap between what its website advertises as released and what its public repositories actually contain is the most interesting thing about it.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/nmfta/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nmfta/refs/heads/main/apis.yml)

## Scope

- **Position:** Producing
- **Access:** 3rd-Party
- **Type:** standards-body / Specification
- **Host:** National Motor Freight Traffic Association (Trade association division)

## Tags

- API Standards
- DSDC
- Digital FTL Council
- Digital LTL Council
- Freight
- Full Truckload
- LTL
- Less-Than-Truckload
- Logistics
- NMFTA
- OpenAPI
- Standards
- Standards Body
- Supply Chain
- Transportation
- Trucking

## Timestamps

- **Created:** 2026-08-03
- **Modified:** 2026-08-03

## APIs

### DSDC LTL eBOL API

The Digital LTL Council's electronic bill of lading standard, version 2.1.0 — the council's first and most adopted contract. This is the standard's own specification, not any carrier's implementation.

- **Human URL:** [https://dsdc.nmfta.org/apis/ebol-api-standard](https://dsdc.nmfta.org/apis/ebol-api-standard)

#### Tags

- eBOL
- Bill of Lading
- LTL

#### Properties

- [Open API](openapi/nmfta-dsdc-ltl-ebol-2.1.0-openapi.yml)
- [Documentation](https://dsdc.nmfta.org/apis/ebol-api-standard)

### DSDC LTL Preliminary Freight Charges API

Gives shippers, carriers and 3PLs visibility into freight charges as they evolve — reclassifications, reweighs and accessorial changes mid-shipment rather than weeks later on the invoice. The only LTL specification committed to the public DSDC repositories.

- **Human URL:** [https://dsdc.nmfta.org/apis/preliminary-freight-charges-api-standard](https://dsdc.nmfta.org/apis/preliminary-freight-charges-api-standard)

#### Tags

- Freight Charges
- Pricing
- LTL

#### Properties

- [Open API](openapi/nmfta-dsdc-ltl-preliminary-freight-charges-openapi.yml)
- [Source Code](https://github.com/dsdcapis/less-than-truckload)

### DSDC FTL eBOL API

The Digital FTL Council's electronic bill of lading standard. Published in the public repository as 1.0.0-public-preview while the DSDC website advertises 1.1.0 as released.

- **Human URL:** [https://dsdcapis.github.io/full-truckload/](https://dsdcapis.github.io/full-truckload/)

#### Tags

- eBOL
- Bill of Lading
- FTL

#### Properties

- [Open API](openapi/nmfta-dsdc-ftl-ebol-openapi.yml)
- [Source Code](https://github.com/dsdcapis/full-truckload)

### DSDC FTL Rate/Quote API

Full truckload rate and quote exchange between shippers, carriers and intermediaries. Published as 1.0.0-public-preview.

- **Human URL:** [https://dsdcapis.github.io/full-truckload/](https://dsdcapis.github.io/full-truckload/)

#### Tags

- Rate Quote
- Pricing
- FTL

#### Properties

- [Open API](openapi/nmfta-dsdc-ftl-rate-quote-openapi.yml)
- [Source Code](https://github.com/dsdcapis/full-truckload)

### DSDC FTL Invoice and Documents API

Invoicing and supporting document exchange for full truckload movements. Published as 1.0.0-public-preview.

- **Human URL:** [https://dsdcapis.github.io/full-truckload/](https://dsdcapis.github.io/full-truckload/)

#### Tags

- Invoicing
- Documents
- FTL

#### Properties

- [Open API](openapi/nmfta-dsdc-ftl-invoice-and-documents-openapi.yml)
- [Source Code](https://github.com/dsdcapis/full-truckload)

### DSDC FTL In-Transit Visibility API

Shipment status and location events while a full truckload movement is under way. Published as 1.0.0-public-preview; the LTL council's equivalent is still in development.

- **Human URL:** [https://dsdcapis.github.io/full-truckload/](https://dsdcapis.github.io/full-truckload/)

#### Tags

- Visibility
- Tracking
- FTL

#### Properties

- [Open API](openapi/nmfta-dsdc-ftl-in-transit-visibility-openapi.yml)
- [Source Code](https://github.com/dsdcapis/full-truckload)

## Common Properties

- [Portal](https://nmfta.org/)
- [Specification](https://dsdc.nmfta.org/apis)
- [GitHub Organization](https://github.com/dsdcapis)
- [Source Code](https://github.com/dsdcapis)
- [Working Groups](https://dsdc.nmfta.org/digital-ltl-council)
- [Contributing](https://dsdc.nmfta.org/contributor-agreement-form)
- [News](https://dsdc.nmfta.org/news)
- [Events](https://nmfta.org/nmfta-event/2026-dsdc-membership-meeting/)
- [Contact](mailto:dsdc@nmfta.org)
- [Governance](governance/nmfta-governance.yml)
- [Taxonomy](taxonomy/nmfta-taxonomy.yml)
- [Companies](companies/nmfta-companies.yml)
- [Adoption](adoption/nmfta-adoption.yml)
- [Leads](leads/nmfta-new-company-leads.yml)
- [Repositories](repositories/nmfta-repositories.yml)
- [Contributors](contributors/nmfta-contributors.yml)

## Features

- Host: NMFTA, founded 1956; DSDC is a division, not a separate entity
- Councils: Digital LTL (November 2020) and Digital FTL (absorbed the Scheduling Standards Consortium)
- APIs advertised: 10 across the two councils
- Specifications in public repositories: 5 of 10
- GitHub repositories: 6, two of which are named test repositories
- Contributors: 5 humans, 123 total contributions
- Participating companies published as logos: 32
- Participants already in the API Evangelist network: 15
- Regulatory mandate: none — adoption earned on cost and friction
- Server declarations across all six harvested specifications: zero

## Maintainers

**FN:** Kin Lane  
**Email:** info@apievangelist.com  
**URL:** https://apievangelist.com
