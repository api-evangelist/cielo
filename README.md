# Cielo (cielo)

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

Cielo is one of the largest Brazilian card acquirers and a publicly traded company (B3:CIEL3), originally formed as a joint venture between Banco Bradesco and Banco do Brasil. The company processes credit, debit, Pix, QR Code, and boleto transactions for hundreds of thousands of merchants across Brazil, providing both in-person acquiring through its family of Cielo Smart (formerly LIO) Android POS terminals and Tap on Phone, and online payment processing through its e-Commerce API, Checkout, Payment Links, and Braspag gateway. Cielo exposes a broad developer surface through developercielo.github.io and the newer docs.cielo.com.br portal, including APIs for sales, queries, tokenization, 3DS 2.2 authentication, Pix with mTLS, chargeback management, refunds, reconciliation (Conciliador), and merchant promotions, along with open-source SDKs in Python, PHP, Java, C#, Kotlin, Swift, and Dart published from the DeveloperCielo GitHub organization.

**URL:** [https://developercielo.github.io/](https://developercielo.github.io/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Payments
- Acquiring
- Fintech
- Brazil
- Point of Sale
- Card Processing

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Cielo E-commerce API

The Cielo E-commerce API (also known as Cielo API 3.0) is the company's flagship online payment processing API, accepting credit cards from Visa, Mastercard, Amex, Elo, Hipercard, and more, as well as debit with 3DS 2.2, Pix, boleto, QR Code, and installments.

**Human URL:** [https://developercielo.github.io/manual/cielo-ecommerce](https://developercielo.github.io/manual/cielo-ecommerce)

#### Tags

- E-commerce, Payments, Credit Card, Debit Card, Tokenization, Sales

#### Properties

- [Documentation](https://developercielo.github.io/manual/cielo-ecommerce)
- [Sandbox](https://apisandbox.cieloecommerce.cielo.com.br)
- [Authentication](https://developercielo.github.io/manual/cielo-ecommerce#autenticação)
- [SDK — Python (API 3.0)](https://github.com/DeveloperCielo/API-3.0-Python)

### Cielo 3DS 2.2 Authentication API

EMVCo-compliant cardholder authentication exposed via Braspag MPI; shifts chargeback liability to the issuer for authenticated card-not-present transactions.

**Human URL:** [https://developercielo.github.io/manual/3ds](https://developercielo.github.io/manual/3ds)

#### Tags

- 3D Secure, Authentication, Fraud Prevention, Card Not Present

#### Properties

- [Documentation](https://developercielo.github.io/manual/3ds)
- [Sandbox](https://mpisandbox.braspag.com.br)

### Cielo Pix API

Brazilian Central Bank Pix rails surfaced over OAuth 2.0 with certificate-bound tokens and mTLS, covering immediate charges, recurring charges, refunds, and webhooks.

**Human URL:** [https://developercielo.github.io/manual/apipix](https://developercielo.github.io/manual/apipix)

#### Tags

- Pix, Instant Payments, Real-time Payments, mTLS, Brazil

#### Properties

- [Documentation](https://developercielo.github.io/manual/apipix)
- [Sandbox](https://api2.cielo.com.br/sandbox/cielo-pix/v1)

### Cielo Payment Link API

OAuth 2.0-secured API that generates short, shareable payment URLs for social commerce, with mobile SDKs for iOS, Android, and Flutter.

**Human URL:** [https://developercielo.github.io/manual/linkdepagamentos5](https://developercielo.github.io/manual/linkdepagamentos5)

#### Tags

- Payment Link, Checkout, OAuth2, Social Commerce

#### Properties

- [Documentation](https://developercielo.github.io/manual/linkdepagamentos5)
- [SDK — Android](https://github.com/DeveloperCielo/Link-de-Pagamento-Android)
- [SDK — iOS](https://github.com/DeveloperCielo/Link-de-Pagamento-iOS)
- [SDK — Dart/Flutter](https://github.com/DeveloperCielo/Link-de-Pagamento-Dart)

### Cielo Checkout API

Hosted payment-page solution handling card, Pix, and boleto flows end-to-end with PCI scope reduction and webhook notifications.

**Human URL:** [https://developercielo.github.io/manual/checkout-cielo](https://developercielo.github.io/manual/checkout-cielo)

#### Tags

- Checkout, Hosted Payment Page, E-commerce

#### Properties

- [Documentation](https://developercielo.github.io/manual/checkout-cielo)
- [GitHubRepository](https://github.com/DeveloperCielo/Checkout-Cielo)
- [SDK — PHP Library](https://github.com/DeveloperCielo/CheckoutCielo-Library)

### Cielo Refunds API

OAuth 2.0 (Keycloak) plus mTLS API for single and batch refund requests, with PDF and ZIP letter generation.

**Human URL:** [https://developercielo.github.io/manual/api-refunds](https://developercielo.github.io/manual/api-refunds)

#### Tags

- Refunds, Cancellations, OAuth2, mTLS

#### Properties

- [Documentation](https://developercielo.github.io/manual/api-refunds)
- [Sandbox](https://apihml-internet.cielo.com.br/refunds-api/v1)

### Cielo Chargeback API

Programmatic dispute lifecycle management — accept, refuse, query, and download issuer evidence — secured by OAuth 2.0 and mTLS.

**Human URL:** [https://developercielo.github.io/manual/api-chargeback-2-0](https://developercielo.github.io/manual/api-chargeback-2-0)

#### Tags

- Chargeback, Disputes, OAuth2, mTLS

#### Properties

- [Documentation](https://developercielo.github.io/manual/api-chargeback-2-0)
- [Sandbox](https://apihml-internet.cielo.com.br/cielo-chargeback-sys-sandbox/chargeback/v1/)

### Cielo Conciliador API

F360-powered reconciliation API exposing card installments, title installments, bank statements, and asynchronous report generation with webhook callbacks.

**Human URL:** [https://developercielo.github.io/manual/edi-cielo-conciliador](https://developercielo.github.io/manual/edi-cielo-conciliador)

#### Tags

- Reconciliation, Conciliation, Reports, Webhooks, F360

#### Properties

- [Documentation](https://developercielo.github.io/manual/edi-cielo-conciliador)

### Cielo Promo API

OAuth 2.0 authorization-code API for distributing merchant promotions and discounts to cardholders through partner apps.

**Human URL:** [https://developercielo.github.io/manual/promotions](https://developercielo.github.io/manual/promotions)

#### Tags

- Promotions, Discounts, Loyalty, OAuth2

#### Properties

- [Documentation](https://developercielo.github.io/manual/promotions)
- [Sandbox](https://api.cielo.com.br/sandbox/promotions/v1)

### Cielo LIO Remote Integration API

Cloud API for driving Cielo Smart (formerly LIO) Android POS terminals from ERP and commercial-automation systems, with Java, Android, C#, PHP, and Kotlin SDKs.

**Human URL:** [https://developercielo.github.io/manual/cielo-lio](https://developercielo.github.io/manual/cielo-lio)

#### Tags

- Point of Sale, LIO, Cielo Smart, Remote Integration, In-Person Payments

#### Properties

- [Documentation](https://developercielo.github.io/manual/cielo-lio)
- [SDK — Java](https://github.com/DeveloperCielo/LIO-SDK-API-Integracao-Remota-v1-Java)
- [SDK — Android](https://github.com/DeveloperCielo/LIO-SDK-API-Integracao-Remota-v1-Android)
- [SDK — C#](https://github.com/DeveloperCielo/LIO-SDK-API-Integracao-Remota-v1-CSHARP)
- [SDK — PHP](https://github.com/DeveloperCielo/LIO-SDK-API-Integracao-Remota-v1-PHP)
- [SDK — Local Integration Sample (Kotlin)](https://github.com/DeveloperCielo/LIO-SDK-Sample-Integracao-Local)
- [SDK — Flutter Hybrid Sample](https://github.com/DeveloperCielo/LIO-Hybrid-Integration-Sample-Flutter)
- [GitHubRepository — Order Manager](https://github.com/DeveloperCielo/order-management)

### Cielo BIN Query API

BIN lookup service exposing card metadata so e-commerce checkouts can validate brand and card type before authorization.

**Human URL:** [https://developercielo.github.io/manual/cielo-ecommerce](https://developercielo.github.io/manual/cielo-ecommerce)

#### Tags

- BIN, Card Validation, Lookup

#### Properties

- [Documentation](https://developercielo.github.io/manual/cielo-ecommerce)
- [SDK — Android](https://github.com/DeveloperCielo/cielo-bin-query-android)
- [SDK — iOS](https://github.com/DeveloperCielo/cielo-bin-query-ios)
- [SDK — Dart/Flutter](https://github.com/DeveloperCielo/cielo-bin-query-dart)

### Cielo E-Wallets API

Extension of the e-Commerce API for accepting Apple Pay, Google Pay, Samsung Pay, and other digital wallets.

**Human URL:** [https://developercielo.github.io/manual/e-wallets-ecommercecielo](https://developercielo.github.io/manual/e-wallets-ecommercecielo)

#### Tags

- Wallets, Digital Wallets, Apple Pay, Google Pay

#### Properties

- [Documentation](https://developercielo.github.io/manual/e-wallets-ecommercecielo)

### Cielo Tap on Phone

SoftPOS solution turning NFC-capable smartphones into card acceptance devices with no separate hardware.

**Human URL:** [https://www.cielo.com.br/maquininha-cartao/cielo-tap](https://www.cielo.com.br/maquininha-cartao/cielo-tap)

#### Tags

- Tap to Pay, SoftPOS, Mobile Acceptance, Contactless

#### Properties

- [Documentation](https://www.cielo.com.br/maquininha-cartao/cielo-tap)
- [SDK — Tap on Phone](https://github.com/DeveloperCielo/TapOnPhone)

## Common

- [Portal](https://www.cielo.com.br/)
- [DeveloperPortal](https://developercielo.github.io/)
- [Documentation](https://docs.cielo.com.br/)
- [Console](https://minhaconta.cielo.com.br/)
- [SignUp](https://www.cielo.com.br/credenciamento)
- [Pricing](https://www.cielo.com.br/maquininha-cartao)
- [GettingStarted](https://developercielo.github.io/tutorial/)
- [APIReference](https://developercielo.github.io/manual/cielo-ecommerce)
- [Support](https://atendimento.cielo.com.br/)
- [Hub — Investor Relations](https://ri.cielo.com.br/)
- [Blog](https://www.cielo.com.br/blog/)
- [GitHubOrganization](https://github.com/DeveloperCielo)
- [GitHubRepository — Developer Site](https://github.com/DeveloperCielo/developercielo.github.io)
- [Tutorials](https://github.com/DeveloperCielo/Tutorial)
- [LinkedIn](https://www.linkedin.com/company/cielo)
- [YouTube](https://www.youtube.com/user/cielobrasil)
- [StackOverflow](https://stackoverflow.com/questions/tagged/cielo)
- [PrivacyPolicy](https://www.cielo.com.br/politica-de-privacidade)
- [TermsOfService](https://www.cielo.com.br/termos-de-uso)
- [BestPractices — E-commerce (Luhn / BIN)](https://github.com/DeveloperCielo/Boas-praticas-de-ecommerce)

## Features

- One of the largest Brazilian card acquirers, listed on B3 as CIEL3
- Originally a joint venture of Banco Bradesco and Banco do Brasil
- Accepts 80+ card brands, Pix, QR Code, NFC, and boleto
- Family of Cielo Smart (formerly LIO) Android POS terminals (Flash, Smart)
- SoftPOS via Cielo Tap (Tap on Phone) — no separate hardware
- Online acquiring via Cielo e-Commerce API (Cielo API 3.0)
- Hosted Cielo Checkout and Payment Links for low-code acceptance
- 3DS 2.2 authentication via Braspag MPI with liability shift
- Tokenization and recurring payments via the e-Commerce API
- Pix via OAuth 2.0 with certificate-bound tokens and mTLS
- Programmatic chargeback and refund lifecycle management
- Financial reconciliation via Cielo Conciliador (F360-powered)
- Promotion distribution to cardholders via Cielo Promo
- Braspag-powered Gateway, Payment Split, and Risk Management
- Pre-built connectors for major Brazilian e-commerce platforms
- Open-source SDKs across Python, PHP, Java, C#, Kotlin, Swift, Dart

## Use Cases

- **In-Person Card Acceptance** — POS acceptance on Cielo Smart Android terminals
- **SoftPOS / Tap on Phone** — Contactless acceptance on NFC smartphones via Cielo Tap
- **Online Card Acquiring** — Cielo e-Commerce API for web and app checkout
- **Hosted Checkout and Payment Links** — Low-code acceptance over shareable URLs
- **Pix Charges and Refunds** — Immediate and recurring Pix with mTLS-secured access
- **3DS 2.2 Authentication** — Liability-shifted CNP authentication via Braspag MPI
- **Dispute and Refund Management** — Bulk chargeback and refund processing
- **Financial Reconciliation** — Card and title installments via the Conciliador API
- **Recurring Payments and Tokenization** — Card-on-file billing with Zero Auth
- **Merchant Promotion Distribution** — Discount surfacing through partner apps

## Integrations

- **Banco Bradesco** — Founding shareholder; merchant onboarding channel
- **Banco do Brasil** — Founding shareholder; merchant onboarding channel
- **Braspag** — Cielo subsidiary powering Gateway, Split, Risk, and 3DS MPI
- **F360** — Powers the Cielo Conciliador reconciliation API
- **Banco Central do Brasil (BCB) Pix** — Underlying instant-payments rail
- **Visa, Mastercard, Elo, Amex, Hipercard** — Card schemes (80+ brands total)
- **Apple Pay, Google Pay, Samsung Pay** — Digital wallets via E-Wallets API
- **VTEX, Magento, WooCommerce** — E-commerce connectors on docs.cielo.com.br

## Solutions

- **Cielo e-Commerce** — Online acquiring stack (API, Checkout, Links, 3DS, BIN, Wallets)
- **Cielo Smart (LIO)** — Android POS hardware and software platform
- **Cielo Tap** — SoftPOS / Tap on Phone solution
- **Braspag** — Enterprise gateway, payment split, and risk management
- **Cielo Promo** — Promotion distribution to consumer-facing partner apps
- **Cielo Conciliador** — Reconciliation and back-office reporting (F360)

## Maintainers

- **API Evangelist** — [info@apievangelist.com](mailto:info@apievangelist.com) — [http://apievangelist.com](http://apievangelist.com)
