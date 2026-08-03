# AWS Marketplace (aws-marketplace)

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

AWS Marketplace is a curated digital catalog from Amazon Web Services that lets customers find, buy, deploy, and manage third-party software, SaaS, containers, machine images (AMIs), data products, and professional services that run on AWS. The AWS Marketplace Catalog API enables approved sellers to programmatically manage their products, change sets, and entities, while buyers can integrate procurement workflows with AWS billing.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/aws-marketplace/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/aws-marketplace/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- AWS
- Cloud Marketplace
- Procurement
- SaaS
- Software Distribution
- Catalog

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### AWS Marketplace Catalog API

REST API for AWS Marketplace sellers to programmatically view and update their product entities and change sets in the marketplace catalog.

- **Human URL:** [https://docs.aws.amazon.com/marketplace-catalog/latest/api-reference/welcome.html](https://docs.aws.amazon.com/marketplace-catalog/latest/api-reference/welcome.html)
- **Base URL:** `https://catalog.marketplace.us-east-1.amazonaws.com`

#### Tags

- Catalog
- Entities
- Change Sets
- Seller Products

#### Properties

- [Documentation](https://docs.aws.amazon.com/marketplace-catalog/latest/api-reference/welcome.html)
- [API Reference](https://docs.aws.amazon.com/marketplace-catalog/latest/api-reference/API_Operations.html)
- [C L I](https://awscli.amazonaws.com/v2/documentation/api/latest/reference/marketplace-catalog/index.html)
- [Postman Collection](collections/aws-marketplace.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aws-marketplace.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AWS Marketplace Metering Service API

API used by AWS Marketplace sellers of SaaS and container products to report customer usage and entitlements for billing.

- **Human URL:** [https://docs.aws.amazon.com/marketplacemetering/latest/APIReference/Welcome.html](https://docs.aws.amazon.com/marketplacemetering/latest/APIReference/Welcome.html)
- **Base URL:** `https://metering.marketplace.us-east-1.amazonaws.com`

#### Tags

- Metering
- Billing
- Usage

#### Properties

- [Documentation](https://docs.aws.amazon.com/marketplacemetering/latest/APIReference/Welcome.html)
- [Postman Collection](collections/aws-marketplace.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aws-marketplace.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AWS Marketplace Entitlement Service API

API for AWS Marketplace sellers to determine the entitlement that a customer has to a paid AWS Marketplace product.

- **Human URL:** [https://docs.aws.amazon.com/marketplaceentitlement/latest/APIReference/Welcome.html](https://docs.aws.amazon.com/marketplaceentitlement/latest/APIReference/Welcome.html)
- **Base URL:** `https://entitlement.marketplace.us-east-1.amazonaws.com`

#### Tags

- Entitlement
- SaaS

#### Properties

- [Documentation](https://docs.aws.amazon.com/marketplaceentitlement/latest/APIReference/Welcome.html)
- [Postman Collection](collections/aws-marketplace.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aws-marketplace.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AWS Marketplace Commerce Analytics Service API

API for AWS Marketplace sellers to request and retrieve reports about sales, customer subscriptions, and disbursements.

- **Human URL:** [https://docs.aws.amazon.com/marketplace/latest/APIReference/commerce-analytics-service.html](https://docs.aws.amazon.com/marketplace/latest/APIReference/commerce-analytics-service.html)
- **Base URL:** `https://marketplacecommerceanalytics.us-east-1.amazonaws.com`

#### Tags

- Analytics
- Reports
- Sales

#### Properties

- [Documentation](https://docs.aws.amazon.com/marketplace/latest/APIReference/commerce-analytics-service.html)
- [Postman Collection](collections/aws-marketplace.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aws-marketplace.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://aws.amazon.com/marketplace/)
- [Documentation](https://docs.aws.amazon.com/marketplace/)
- [API Reference](https://docs.aws.amazon.com/marketplace/latest/APIReference/welcome.html)
- [Buyer  Guide](https://docs.aws.amazon.com/marketplace/latest/buyerguide/what-is-marketplace.html)
- [Seller  Guide](https://docs.aws.amazon.com/marketplace/latest/userguide/what-is-marketplace.html)
- [Git Hub  Samples](https://github.com/aws-samples/aws-marketplace-api-samples)
- [Sign Up](https://aws.amazon.com/marketplace/management/signin)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
