# Zerocater

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

Zerocater is a corporate catering and workplace food company that builds and manages office food
programs for businesses, connecting employers to a curated network of local restaurants, caterers and
chefs. It covers daily corporate catering, chef-led on-site corporate cafeterias, and full-service event
catering, and its CaterAi product uses AI to assemble menus from a team's preferences, dietary
restrictions and order history. Zerocater states it serves 500+ companies across 12+ U.S. metros.

## API surface

Zerocater publishes **no** OpenAPI, no developer portal and no API documentation. It does run an
undocumented Django REST Framework JSON API behind its ordering application, and that API serves an
anonymously reachable RFC 6570 URI-template hypermedia index at its root:

- **API root (probed, 200):** https://app.zerocater.com/api/v3 — 23 resource link relations
- **Captured verbatim:** [`discovery/zerocater-api-v3-root.json`](discovery/zerocater-api-v3-root.json)
- **Endpoint inventory + evidence:** [`discovery/zerocater-api-v3-discovery.yml`](discovery/zerocater-api-v3-discovery.yml)

No OpenAPI has been derived from that index and no fabricated specification for Zerocater exists in this
repository. Every artifact here records the URL it was fetched from and the HTTP status it returned.

- Zerocater: https://zerocater.com/
- Ordering application: https://app.zerocater.com/
- GitHub organization: https://github.com/ZeroCater
- First-party Python client: https://github.com/ZeroCater/PyZeroCater (`pip install zerocater`)
- Secondary-market listing: https://forgeglobal.com/zerocater_stock/
