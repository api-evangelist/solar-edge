# SolarEdge

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

SolarEdge Technologies provides a cloud-based Monitoring API that enables web services and third-party applications to access real-time and historical solar production data stored on the SolarEdge monitoring server. The REST API delivers site energy measurements, power flow data, inverter technical telemetry, battery storage status, equipment inventory, and environmental benefit metrics for SolarEdge-connected systems.

Authentication is handled via an API key generated through the SolarEdge monitoring portal, and all requests are made over HTTPS with responses returned in JSON format. The platform supports both site-level and account-level queries, with bulk call options allowing developers to retrieve data across multiple sites in a single request.

**Base URL:** `https://monitoringapi.solaredge.com`

**Authentication:** API key via `api_key` URL query parameter

**Rate Limits:** 300 requests/day per account token, 300 requests/day per site ID from same IP, max 3 concurrent requests

## Links

- **Website:** https://www.solaredge.com
- **Documentation:** https://knowledge-center.solaredge.com/sites/kc/files/se_monitoring_api.pdf
- **GitHub Org:** https://github.com/SolarEdgeTech
- **Blog:** https://www.solaredge.com/us/solaredge-blog
- **LinkedIn:** https://www.linkedin.com/company/solaredge
- **X:** https://x.com/SolarEdgePV

## APIs.json

This repository is an [APIs.json](https://apisjson.org) index for SolarEdge, maintained by [API Evangelist](https://apievangelist.com).

- **APIs.json:** [apis.yml](apis.yml)
- **Plans:** [plans/solar-edge-plans-pricing.yml](plans/solar-edge-plans-pricing.yml)
- **Rate Limits:** [rate-limits/solar-edge-rate-limits.yml](rate-limits/solar-edge-rate-limits.yml)
- **FinOps:** [finops/solar-edge-finops.yml](finops/solar-edge-finops.yml)

**Maintainer:** Kin Lane (kin@apievangelist.com)
