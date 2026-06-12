# Companies House (companies-house)

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
