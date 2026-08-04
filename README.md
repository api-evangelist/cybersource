# CyberSource

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

CyberSource, a Visa solution, is a global payment management platform that enables businesses to accept payments online, in-app, and in-person. It provides REST APIs for payment authorization and processing, fraud management via Decision Manager, payment tokenization, recurring billing, payouts, and comprehensive post-transaction reporting. The platform operates across 190+ countries and supports card-present, card-not-present, digital wallets, alternative payment methods, and buy-now-pay-later integrations.

## Developer Resources

- **Developer Center**: https://developer.cybersource.com/
- **Documentation Hub**: https://docs.cybersource.com/en/main.html
- **API Reference**: https://developer.cybersource.com/api-reference-assets/index.html
- **Getting Started**: https://developer.cybersource.com/docs/cybs/en-us/platform/developer/all/rest/rest-getting-started.html
- **GitHub**: https://github.com/CyberSource
- **Status Page**: https://status.cybersource.com/
- **Release Notes**: https://docs.cybersource.com/en/release-notes/index.html
- **Developer Community**: https://community.developer.cybersource.com/
- **Sandbox**: https://developer.cybersource.com/hello-world/sandbox.html

## APIs

| API | Description |
|-----|-------------|
| Payments API | Authorization, capture, refund, and void for cards and ACH |
| Token Management Service (TMS) | Tokenization and secure storage of payment credentials |
| Decision Manager API | AI-powered fraud detection and risk management |
| Recurring Billing API | Subscription plans and automated recurring charges |
| Payouts API | Direct fund delivery via Visa/Mastercard AFT/OCT |
| Flex Microform API | PCI-compliant hosted payment field tokenization |
| Unified Checkout API | Multi-method checkout widget |
| Payer Authentication (3DS) | 3D Secure 2.x implementation |
| Reporting API | Financial and reconciliation reports |
| Transaction Search API | Historical transaction query and retrieval |
| Webhooks API | Event-driven payment and fraud notifications |
| Boarding API | Merchant account hierarchy management |
| Invoicing API | Invoice creation and pay-by-link |
| BIN Lookup API | Card identification and routing data |
| Intelligent Commerce API | Agent-initiated unified payment APIs |

## Authentication

CyberSource REST APIs use JSON Web Token (JWT) authentication with either P12 certificates or shared secret key pairs. HTTP Signature Security is deprecated and must be migrated to JWT by September 2026. Message-Level Encryption (MLE) is available for additional security.

- **Production**: https://api.cybersource.com
- **Sandbox**: https://apitest.cybersource.com

## Pricing

CyberSource uses a custom/enterprise pricing model negotiated directly with Visa/CyberSource sales. No public rate card is available. A free sandbox environment is available for development and testing.

## Profile

- **APIs.yml**: [apis.yml](apis.yml)
- **Plans**: [plans/plans.yml](plans/plans.yml)
- **Rate Limits**: [rate-limits/rate-limits.yml](rate-limits/rate-limits.yml)
- **FinOps**: [finops/finops.yml](finops/finops.yml)
