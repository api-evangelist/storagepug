# StoragePug (storagepug)

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
