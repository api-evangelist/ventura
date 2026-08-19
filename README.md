# Ventura

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

Ventura (operated by Gradient Ascent Labs, Inc.) builds an AI workforce for industrial
distributors and manufacturers, starting with quoting and order entry: it reads inbound
emails, PDFs, images and phone calls, matches products against the customer's catalog,
drafts a quote or order for a rep to review, and pushes the approved result into the
customer's ERP.

**No public API surface.** As of 2026-08-14 the enrichment pipeline found no developer
portal, documentation, API reference, OpenAPI/AsyncAPI/GraphQL contract, MCP server,
agent card, SDK, or `/.well-known/` discovery document on any Ventura host.
`api.ventura.ai`, `docs.ventura.ai` and `developer.ventura.ai` do not resolve; the
marketing site's sitemap lists only the homepage and the privacy policy; and the customer
application at `app.ventura.ai` redirects every path to `/authenticate`. What is captured
here is what the company publishes: a domain-security probe, a recorded `/.well-known/`
absence, a self-asserted SOC 2 Type II compliance claim, and a contact-sales-only pricing
posture. See `x-coverage` in `apis.yml`.

Backed by: y-combinator
