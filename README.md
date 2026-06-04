# Queen's University at Kingston (queens-university-at-kingston)

Queen's University at Kingston is a public research university in Kingston, Ontario, Canada, serving more than 25,000 students and ranked #193 in the QS World University Rankings 2025. This repository catalogs the institution's public developer and API footprint as an [APIs.json](http://apisjson.org/) profile. Queen's does not run a single official developer portal; its programmatic surfaces are mostly community- and library-operated, centered on the Qmulus open-data API, the QSpace institutional repository, and the Queen's University Dataverse.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/queens-university-at-kingston/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=queens-university-at-kingston-api-evangelist&utm_content=repo

## Type

- Type: Index
- Position: Consumer
- Access: 3rd-Party

## Tags

Education, Higher Education, University, Open Data, Research Data, Library, Canada

## APIs

- **Qmulus Open Data API** — community-run open-data REST API for Queen's datasets (courses, buildings, textbooks). Token-gated to @queensu.ca emails. Docs: https://docs.qmulus.io / Site: https://qmulus.io/ / GitHub: https://github.com/queens-qmulus/qmulus
- **QSpace Repository API (DSpace)** — open-access institutional repository with DSpace REST and OAI-PMH. https://qspace.library.queensu.ca/ — OAI-PMH: https://qspace.library.queensu.ca/server/oai/request?verb=Identify
- **Queen's University Dataverse (Borealis)** — research data repository on the Canadian Borealis Dataverse, with native REST, OAI-PMH, and SWORD. Docs: https://borealisdata.ca/guides/en/latest/api/native-api.html — OAI-PMH: https://borealisdata.ca/oai?verb=Identify

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/queens-university-at-kingston-plans-pricing.yml](plans/queens-university-at-kingston-plans-pricing.yml)
- Rate Limits: [rate-limits/queens-university-at-kingston-rate-limits.yml](rate-limits/queens-university-at-kingston-rate-limits.yml)
- FinOps: [finops/queens-university-at-kingston-finops.yml](finops/queens-university-at-kingston-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.queensu.ca/
- GitHub: https://github.com/queens-qmulus
- LinkedIn: https://ca.linkedin.com/school/queen's-university/
- Library: https://library.queensu.ca/
- Review: [review.yml](review.yml)

## Notes

All URLs were probed during review on 2026-06-03. The Qmulus docs and landing pages are live, but its documented API host `api.qmulus.io` did not resolve at review time and token signup is restricted to @queensu.ca accounts. The QSpace DSpace REST/OAI-PMH endpoints (under the DSpace 7 `/server` path) and the Borealis Dataverse OAI-PMH endpoint were verified live. No endpoints were fabricated; gated or non-resolving surfaces are noted honestly in [review.yml](review.yml).

## Maintainers

- Kin Lane — kin@apievangelist.com
