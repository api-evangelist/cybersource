# CyberSource

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
