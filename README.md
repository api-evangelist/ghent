# Ghent University (ghent)

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
