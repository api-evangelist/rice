# Rice University (rice)

Rice University is a private research university in Houston, Texas, ranked #141 in the QS World University Rankings 2025. This repository catalogs Rice's public developer/API footprint as an [APIs.json](https://apisjson.org/) profile. The most substantive API surface is Fondren Library's Rice Research Repository (DSpace 9.x) via its REST API and OAI-PMH interface, alongside a Shibboleth SAML identity provider and a public course schedule.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/rice/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=rice-api-evangelist&utm_content=repo

## Type

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Education, Higher Education, University, Research, Library, Open Repository, United States

## APIs

- **Rice Research Repository REST API** — DSpace 9.x REST API for the institutional repository (R-3). Docs: https://repository.rice.edu/server/api
- **Rice Research Repository OAI-PMH** — OAI-PMH 2.0 metadata harvesting endpoint. Docs: https://repository.rice.edu/server/oai/request?verb=Identify
- **Rice Shibboleth SAML Identity Provider** — Federated SSO IdP publishing SAML metadata. Docs: https://idp.rice.edu/idp/shibboleth
- **Rice University Course Schedule** — Public course catalog/schedule query interface. Docs: https://registrar.rice.edu/students/courses

## Plans, Rate Limits & FinOps

- [Plans & Pricing](plans/rice-plans-pricing.yml)
- [Rate Limits](rate-limits/rice-rate-limits.yml)
- [FinOps](finops/rice-finops.yml)

## Timestamps

- **Created:** 2026-06-03
- **Modified:** 2026-06-03

## Common Properties

- Website: https://www.rice.edu/
- GitHub: https://github.com/RiceUniversity (official org; no public repos)
- LinkedIn: https://www.linkedin.com/school/rice-university/
- Status: https://status.rice.edu/
- Authentication: https://idp.rice.edu/idp/shibboleth

## Notes

All endpoints were probed live on 2026-06-03. The Rice Research Repository REST API and OAI-PMH endpoints returned HTTP 200 and identified as "Rice Research Repository" (DSpace 9.3). The Shibboleth IdP serves valid SAML metadata. The course schedule is a queryable web interface rather than a formally documented REST/JSON API. The official RiceUniversity GitHub org exists but has zero public repositories. A legacy third-party RiceAPI (api.riceapps.org) did not resolve and was excluded. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
