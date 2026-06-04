# University of Glasgow (university-of-glasgow)

The University of Glasgow is a public research university in Glasgow, Scotland, United Kingdom, founded in 1451 and ranked #62 in the QS World University Rankings 2025. This repository catalogs the institution's public developer and API footprint as an APIs.json provider profile for the api-evangelist network. Glasgow does not operate a single unified developer portal; its confirmed machine-accessible surface is centered on EPrints-based scholarly repositories exposing OAI-PMH, with departmental open-source code on GitHub and most internal systems gated behind Shibboleth/SAML single sign-on.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-glasgow/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-glasgow-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Access, Repository, OAI-PMH, United Kingdom, Scotland

## APIs

- **Enlighten Publications OAI-PMH** — OAI-PMH 2.0 metadata harvesting for the EPrints institutional publications repository. Docs: https://eprints.gla.ac.uk/information.html — Base URL: https://eprints.gla.ac.uk/cgi/oai2
- **Enlighten Research Data OAI-PMH** — OAI-PMH 2.0 metadata harvesting for the EPrints research data repository and registry. Docs: https://researchdata.gla.ac.uk/ — Base URL: https://researchdata.gla.ac.uk/cgi/oai2

## Plans

- [Plans & Pricing](plans/university-of-glasgow-plans-pricing.yml)

## Rate Limits

- [Rate Limits](rate-limits/university-of-glasgow-rate-limits.yml)

## FinOps

- [FinOps](finops/university-of-glasgow-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.gla.ac.uk/
- GitHub: https://github.com/UoGSoE (School of Engineering IT; departmental, not a university-wide org)
- LinkedIn: https://www.linkedin.com/school/university-of-glasgow/
- Authentication: https://www.gla.ac.uk/myglasgow/it/ (Shibboleth/SAML SSO via GUID)

## Notes

- All endpoints were probed during research; both OAI-PMH endpoints returned HTTP 200 and the Research Data endpoint returned a valid `Identify` response.
- No unified API developer portal, public SignUp, documented rate limits, or pricing were found. No endpoints were fabricated.
- No single official university-wide GitHub organization exists (`github.com/UofGlasgow` returns 404); only departmental/research orgs were confirmed.
- The LinkedIn school page returns HTTP 999 to automated requests (LinkedIn anti-bot); the page exists publicly.

## Maintainers

- Kin Lane — kin@apievangelist.com
