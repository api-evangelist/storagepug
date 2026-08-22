# StoragePug (storagepug)

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

StoragePug builds marketing websites, online rental/reservation flows, and lead-management dashboards for self-storage facility operators. **StoragePug has no public developer API.** There is no self-service developer portal, no published REST/GraphQL API reference, and no OpenAPI specification. StoragePug's documented "API integration" work actually runs the other direction: StoragePug is a licensed integration partner that consumes property-management-system (PMS) APIs - primarily SiteLink's API, with additional PMS partners such as CallPotential and OpenTech Alliance/StorageTreasures - to pull unit rates, availability, and tenant data into the facility websites it builds, and to push back online rentals, reservations, and payments. No webhook system, API key management screen, or Zapier app for StoragePug itself was found. This repository is documented as a stub because there is no public API to catalog.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/storagepug/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/storagepug/refs/heads/main/apis.yml)

## Tags

- Self Storage
- Marketing Websites
- Lead Generation
- Property Management Software
- SiteLink Integration
- No Public API

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## APIs

None. StoragePug does not publish a public API. See [review.yml](review.yml) for the full findings.

## What StoragePug Actually Integrates With (not a public API)

StoragePug's own help center and blog document how StoragePug, on behalf of a facility operator, connects to that facility's property-management system:

- **SiteLink** - the primary PMS partner. Facility staff create a dedicated SiteLink API user and hand the credentials to StoragePug, which then reads unit rates/availability/tenant data and writes back online rentals, reservations, autopay setup, and tenant insurance purchases through SiteLink's API.
- **CallPotential** and **OpenTech Alliance / StorageTreasures** - additional PMS/marketplace partners referenced in StoragePug's support content.

None of this is an API a third-party developer can register against on StoragePug's own platform - it is StoragePug consuming other companies' APIs to power the websites it sells.

## Pricing (not API pricing)

StoragePug sells per-facility website/marketing subscriptions:

- **Professional** - $150/month (staff accounts, unlimited units)
- **Pug Partnership** - full website + marketing + PMS-integration toolkit; quote-only
- **Enterprise** - custom scope; quote-only

A third-party listing (Capterra/GetApp) separately cites "$100 per user, per month" as a starting price, which does not match the current storagepug.com/plans page; both are recorded in [plans/storagepug-plans-pricing.yml](plans/storagepug-plans-pricing.yml) for transparency. See that file for full details.

## Common Properties

- [Website](https://www.storagepug.com)
- [LinkedIn](https://www.linkedin.com/company/storagepug)
- [Help Center](https://help.storagepug.com/en)
- [Documentation](https://www.storagepug.com/blog/tag/api-integration)
- [GitHub Organization](https://github.com/storagepug)
- [Plans](plans/storagepug-plans-pricing.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
