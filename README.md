# University of Glasgow (university-of-glasgow)

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
