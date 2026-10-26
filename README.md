# Finaeo (finaeo)

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

Finaeo Inc. is a Toronto-based Canadian insurtech operating a digital marketplace that connects life insurance carriers, independent brokers and their clients. Its platform gives independent life brokers a product marketplace across carriers and hundreds of products, side-by-side product comparison and quoting, a place-a-policy checkout flow with selected carriers, a white-labeled client portal with digital onboarding and custom Financial Needs Assessments, contact and document management, broker landing pages, and team and distributor white-label offerings. Its home market is Canada, with expansion into the United States through IMO and broker-agency partnerships. Finaeo is a distribution and agency technology vendor, not a risk carrier.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/finaeo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/finaeo/refs/heads/main/apis.yml)

## Tags

- Insurance
- Canada
- Life Insurance
- Insurtech
- Broker
- Agency Management
- Marketplace
- Distribution
- Quoting
- Policy Administration

## Timestamps

- **Created:** 2026-07-25
- **Modified:** 2026-07-25

## APIs

**None.** Finaeo publishes no public API.

There is no developer portal, no API reference, no downloadable OpenAPI or Swagger
document, no SDK, no Postman collection, no GraphQL surface and no webhook or event
catalog. No `developer`, `developers`, `docs`, `api`, `app`, `portal` or `sandbox`
subdomain resolves in DNS, and a sweep of 2,840 unique archived first-party URLs
turns up no developer path of any kind.

Finaeo's own carrier-facing marketing positions the product explicitly *against*
APIs. Verbatim from the homepage carrier section:

> Leverage a complete no-code toolkit to digitize products, configure applications,
> and launch custom workflows directly into Finaeo's marketplace. This dramatically
> speeds up the launch process **without the need for bulky APIs**.

The only documented carrier integration is bilateral and partner-negotiated: a May
2021 launch with Empire Life that pushes client data collected in Finaeo into Empire
Life's "Fast & Full Life Application" platform so brokers do not re-key it. Finaeo
called it "the first of its kind on the Finaeo platform," and noted that "for
non-integrated carriers, Finaeo also offers a 'no-code' option to integrate
applications directly into their system."

Everything operational sits behind a broker login or a book-a-demo form. Finaeo is a
**partner-gated provider with zero public self-serve API surface**, and that is
recorded here as the finding rather than papered over.

### ACORD posture

**No ACORD reference found.** Zero matches for ACORD, AL3, ACORD XML, NGDS, IVANS,
agency download, Applied Epic, Vertafore or AMS360 anywhere across Finaeo's public
site or its archived history. Finaeo is a life-side distribution platform, and the
North American life channel sits outside the P&C ACORD/AL3/IVANS agency-download
rails — consistent with the segment, but an absence all the same.

### Quote / Bind / Issue / FNOL

| Verb | Exposed | Surface | Audience |
| --- | --- | --- | --- |
| Quote | Yes | In-product only, no API | Agent-facing |
| Bind | Partial — "available with a limited selection of carriers" | In-product only, no API | Agent-facing |
| Issue | No | Happens at the carrier | — |
| FNOL | No | Not a claims platform | — |

## Properties

- [Website](https://www.finaeo.com/)
- [Login](https://www.finaeo.com/login/)
- [Signup](https://www.finaeo.com/signup/)
- [Pricing](https://www.finaeo.com/pricing/)
- [Blog](https://www.finaeo.com/blog/)
- [Security](https://www.finaeo.com/security/)
- [Terms of Service](https://www.finaeo.com/terms-of-use/)
- [Privacy Policy](https://www.finaeo.com/privacy-policy/)
- [Marketplace](https://www.finaeo.com/marketplace/)
- [Client Portal](https://www.finaeo.com/client-portal/)
- [Support](https://www.finaeo.com/contactus/)
- [GitHub Organization](https://github.com/FinaeoInc)
- [LinkedIn](https://www.linkedin.com/company/finaeo)
- [X (Twitter)](https://twitter.com/finaeohq)
- [YouTube](https://www.youtube.com/channel/UCe3BqBc3dM93Nr7irYMkFEw)

## Review

See [review.yml](review.yml) for the full API Evangelist reviewer findings —
every probed URL with its HTTP status, the ACORD sweep, the quote/bind/issue/FNOL
breakdown, the auth model, and the company profile.

> Note: `https://finaeo.com/` is live but fronted by a Cloudflare bot challenge, so
> every path returns HTTP 403 to non-browser clients. Page content was confirmed
> through Internet Archive captures (most recent read: 2025-11-07). The DNS results
> for the developer/docs/api subdomains are unaffected by that challenge — those
> hosts simply do not exist.

## Market context

Canada has the most fragmented insurance supervision of the four markets in this
study: OSFI supervises federally-regulated insurers prudentially while the provinces
regulate market conduct (FSRA in Ontario, AMF in Quebec). There is no open-insurance
mandate, and Consumer-Driven Banking — Canada's open-banking framework — excludes
insurance entirely. With no forcing function, a distribution-layer vendor like Finaeo
has no regulatory reason to publish an API, and it does not. Its stated strategy is
the opposite: sell carriers a no-code onboarding path so they never have to build one
either.
