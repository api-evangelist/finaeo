# Finaeo (finaeo)

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
