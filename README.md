# Companies House (companies-house)

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

Companies House is the UK government executive agency responsible for incorporating and dissolving limited companies and registering company information in Great Britain. The Companies House REST API provides a free, open, and standardised way for developers to search and retrieve company registration data, including company profiles, officer appointments, persons of significant control, filing history, charges, and insolvency records. A real-time Streaming API is also available, delivering changes to Companies House data as they happen. All access is provided free of charge and requires only an API key obtained from the Companies House Developer Hub. Authentication uses HTTP Basic Auth with the API key as the username.

APIs.json: https://raw.githubusercontent.com/api-evangelist/companies-house/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=companies-house-api-evangelist&utm_content=repo

## Tags

- Companies
- UK Government
- Business Registration
- Company Search
- Officers
- Filing History
- Insolvency
- Charges
- Persons of Significant Control
- Open Data

## APIs

| API | Description |
|-----|-------------|
| Companies House Public Data API | Read access to all publicly available UK company data including profiles, officers, filing history, charges, insolvency, and PSC information |
| Companies House Streaming API | Real-time streaming of Companies House data changes via long-running HTTP connections across nine data categories |

## Plans, Rate Limits, and FinOps

| Resource | File |
|----------|------|
| Plans and Pricing | [plans/companies-house-plans-pricing.yml](plans/companies-house-plans-pricing.yml) |
| Rate Limits | [rate-limits/companies-house-rate-limits.yml](rate-limits/companies-house-rate-limits.yml) |
| FinOps | [finops/companies-house-finops.yml](finops/companies-house-finops.yml) |

**Pricing:** Free — no charges for API access. A single free tier with 600 requests per 5-minute window is available to all registered developers. Higher limits available by contacting Companies House directly.

**Rate Limits:**
- Public Data API: 600 requests per 5-minute window per API key (HTTP 429 on breach)
- Streaming API: 2 concurrent connections per account

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common

| Type | URL |
|------|-----|
| Website | https://www.gov.uk/government/organisations/companies-house |
| Documentation | https://developer.company-information.service.gov.uk/overview |
| GitHub Org | https://github.com/companieshouse |
| LinkedIn | https://www.linkedin.com/company/companies-house |
| Blog | https://companieshouse.blog.gov.uk |
| Pricing | https://developer.company-information.service.gov.uk/overview |
| Status Page | https://forum.companieshouse.gov.uk/c/api-changes/7 |
| X | https://x.com/CompaniesHouse |
| Forum | https://forum.companieshouse.gov.uk |
| Authentication | https://developer-specs.company-information.service.gov.uk/guides/authorisation |

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
