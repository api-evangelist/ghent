# Ghent University (ghent)

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

Ghent University (Universiteit Gent, UGent) is a major public research university in Ghent, Belgium, ranked #169 in the QS World University Rankings 2025. Its public developer footprint is led by the Ghent University Library, whose Academic Bibliography and catalog expose documented REST, OAI-PMH, SRU, IIIF and OpenSearch interfaces, alongside the community-maintained Hydra Resto API from the Zeus WPI student group. This repository catalogs that footprint as an [APIs.json](https://apisjson.org) profile.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ghent/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ghent-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, Library, Open Data, Belgium, Europe

## APIs

- **Ghent University Academic Bibliography API** — REST publication search (JSON/JSONP), plus OAI-PMH, SRU, unAPI and bulk dumps. Docs: https://biblio.ugent.be/doc/api
- **Academic Bibliography OAI-PMH** — Metadata harvesting endpoint (`https://biblio.ugent.be/oai`). Docs: https://biblio.ugent.be/doc/api
- **Academic Bibliography SRU** — SRU 1.1 / CQL search (`https://biblio.ugent.be/sru`). Docs: https://biblio.ugent.be/doc/api
- **Ghent University Library Catalog Interfaces** — OAI-PMH, SRU, IIIF (v2) and OpenSearch over library collections. Docs: https://lib.ugent.be/catalog
- **Hydra Resto API (Zeus WPI)** — Community JSON API for UGent student-restaurant menus (`https://hydra.ugent.be/api/2.0/resto`). Docs: https://github.com/ZeusWPI/hydra/blob/master/api-resto-02.md

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/ghent-plans-pricing.yml](plans/ghent-plans-pricing.yml)
- Rate Limits: [rate-limits/ghent-rate-limits.yml](rate-limits/ghent-rate-limits.yml)
- FinOps: [finops/ghent-finops.yml](finops/ghent-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.ugent.be/en
- GitHub (official org): https://github.com/ugent
- Source Code (library org): https://github.com/ugent-library
- LinkedIn: https://www.linkedin.com/school/ghent-university/
- Review: [review.yml](review.yml)

## Notes

All endpoints in this profile were probed live during research and returned HTTP 200 unless noted otherwise; nothing was fabricated. The Academic Bibliography (biblio.ugent.be) and library catalog (lib.ugent.be) are official UGent Library services. The Hydra Resto API is maintained by Zeus WPI, the UGent computer-science student working group, and is not an official university service. No centralized institutional developer portal or API gateway with sign-up/keys was found; APIs are documented per service. The legacy `lib.ugent.be/en/info/open` and `/en/info/exports` info pages returned 404 and were excluded.

## Maintainers

- Kin Lane — kin@apievangelist.com
