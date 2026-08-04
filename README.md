# Kevel (kevel)

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

Kevel is an API-first ad serving platform that lets brands and publishers build unified, fully customized ad systems supporting any ad format, any creative, and multiple demand sources. Kevel exposes a Decision API for ad requests, a Management API for campaign and creative operations, a Reporting API for performance analytics, and a UserDB API for first-party audience and user data.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/kevel/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/kevel/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Ad Serving
- Advertising
- API-First
- Audience
- Monetization
- Reporting

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-28

## APIs

### Kevel Decision API

The Decision API enables ad requests without using ad code. By posting to a RESTful endpoint, Kevel's ad engine returns decision data and creative contents for serving ads in your application across web, mobile, native, audio, video, and CTV surfaces.

- **Human URL:** [https://dev.kevel.com/reference/request](https://dev.kevel.com/reference/request)

#### Tags

- Ad Serving
- Decision
- Native Ads

#### Properties

- [Documentation](https://dev.kevel.com/docs/native-ads-api-quickstart)
- [Reference](https://dev.kevel.com/reference/request)
- [Postman Collection](collections/kevel.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kevel.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kevel Management API

The Management API provides programmatic access to manage advertisers, campaigns, flights, ads, creatives, channels, sites, zones, and other platform resources. It is the system-of-record API used to provision and operate the Kevel ad server.

- **Human URL:** [https://dev.kevel.com/docs/management-api-tutorial](https://dev.kevel.com/docs/management-api-tutorial)

#### Tags

- Campaigns
- Creatives
- Management

#### Properties

- [Documentation](https://dev.kevel.com/docs/management-api-tutorial)
- [Reference](https://dev.kevel.com/reference/getting-started-with-the-management-api)
- [Postman Collection](collections/kevel.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kevel.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kevel Reporting API

The Reporting API exposes ad serving performance data, allowing customers to pull impressions, clicks, conversions, revenue, and other metrics by advertiser, campaign, flight, ad, creative, site, zone, and date range for analytics and finance workflows.

- **Human URL:** [https://dev.kevel.com/reference/reporting-overview](https://dev.kevel.com/reference/reporting-overview)

#### Tags

- Analytics
- Reporting

#### Properties

- [Documentation](https://dev.kevel.com/reference/reporting-overview)
- [Postman Collection](collections/kevel.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kevel.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kevel UserDB API

The UserDB API provides first-party audience and user data management, enabling customers to read and write user keys, custom properties, interests, and audience segment membership for targeting in the Decision API.

- **Human URL:** [https://dev.kevel.com/reference/userdb-overview](https://dev.kevel.com/reference/userdb-overview)

#### Tags

- Audience
- Targeting
- UserDB

#### Properties

- [Documentation](https://dev.kevel.com/reference/userdb-overview)
- [Postman Collection](collections/kevel.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kevel.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/kevelapi)
- [Website](https://www.kevel.com)
- [Portal](https://dev.kevel.com/)
- [Documentation](https://dev.kevel.com/docs/understanding-kevel)
- [Getting Started](https://dev.kevel.com/reference/getting-started-with-kevel)
- [Reference](https://dev.kevel.com/reference)
- [S D Ks](https://dev.kevel.com/docs/sdks)
- [Blog](https://www.kevel.com/blog)
- [Pricing](https://www.kevel.com/pricing)
- [L L Ms Txt](https://dev.kevel.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
