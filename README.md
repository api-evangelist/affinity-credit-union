# Affinity Credit Union

Affinity Credit Union is a member-owned financial cooperative headquartered in
Saskatoon, Saskatchewan, Canada. Formed in 2005 through the amalgamation of
several Saskatchewan credit unions, it is the largest credit union in
Saskatchewan and among the ten largest in Canada, with roughly CAD 9.6 billion
in managed assets. Operating under a "Banking on Values" mandate, Affinity
provides personal and business banking, lending, mortgages, and investment
services across a province-wide network, and is democratically owned and
governed by its members.

## Open Finance & API Posture

Affinity Credit Union exposes **no first-party public developer API and runs no
developer portal.** Probes of `developer.affinitycu.ca`, `developers.affinitycu.ca`,
and `api.affinitycu.ca` did not resolve; only the member-facing marketing and
online-banking site at `www.affinitycu.ca` is live. This is the normal, honest
posture for a Canadian credit union of this size.

- **Charter / ownership.** Provincially regulated member-owned cooperative
  (credit union), not a Schedule I/II bank.
- **Core & digital banking.** Delivered through the credit-union system's
  banking-technology rails (Central 1), not a self-built public API.
- **Consumer data access today.** Third-party access is aggregator /
  screen-scraping based (e.g. Flinks, Plaid, MX, Salt Edge), not a first-party
  data-sharing API.
- **Consumer-Driven Banking (CDB).** Canada's federal Consumer-Driven Banking
  framework (Budget 2024 / Fall Economic Statement 2024, overseen by the
  Financial Consumer Agency of Canada, FCAC) is legislated but **not yet
  operational.** Affinity is a stated supporter of the credit-union-system
  "Open Banking Solution" being delivered by Caspian One under the Large Credit
  Union Coalition, positioning it for that coming framework. No CDB/FDX
  production endpoint is published.
- **Rails.** No documented first-party API around Interac or the Payments Canada
  Real-Time Rail (RTR); participation is via the shared credit-union system.

## Links

- Website: https://www.affinitycu.ca/
- Support / Contact: https://www.affinitycu.ca/contact-us/
- Security: https://www.affinitycu.ca/security
- Privacy Policy: https://www.affinitycu.ca/privacy/policy
- Legal / Terms: https://www.affinitycu.ca/legal
- News: https://www.affinitycu.ca/meet-affinity/news
- LinkedIn: https://ca.linkedin.com/company/affinity-credit-union

## Maintainers

- Kin Lane — kin@apievangelist.com
