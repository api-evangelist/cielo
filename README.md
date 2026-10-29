# Cielo

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

Cielo is one of the largest Brazilian card acquirers and a publicly traded company (B3:CIEL3), originally formed as a joint venture between Banco Bradesco and Banco do Brasil. The company processes credit, debit, Pix, QR Code, and boleto transactions for hundreds of thousands of merchants across Brazil, providing both in-person acquiring through its family of Cielo Smart (formerly LIO) Android POS terminals and Tap on Phone, and online payment processing through its e-Commerce API, Checkout, Payment Links, and Braspag gateway. Cielo exposes a broad developer surface through developercielo.github.io and the newer docs.cielo.com.br portal, including APIs for sales, queries, tokenization, 3DS 2.2 authentication, Pix with mTLS, chargeback management, refunds, reconciliation (Conciliador), and merchant promotions, along with open-source SDKs in Python, PHP, Java, C#, Kotlin, Swift, and Dart published from the DeveloperCielo GitHub organization.

**Areas:** Payments · Acquiring · Fintech · Brazil · Point-of-Sale · Card Processing

## Cielo on APIs.io

Everything profiled for Cielo is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cielo/](https://apis.io/providers/cielo/)** — or go straight to one of the APIs or properties below.

### APIs (13)

- [Cielo E-commerce API](https://apis.io/apis/cielo/cielo-ecommerce-api/) — The Cielo E-commerce API (also known as Cielo API 3.0) is the company's flagship online payment processing API. It accepts credit cards from Visa,…
- [Cielo 3DS 2.2 Authentication API](https://apis.io/apis/cielo/cielo-3ds-api/) — Cielo 3DS 2.2 is an EMVCo-compliant cardholder authentication service exposed via the Braspag MPI endpoint. It confirms that the buyer is the legitimate…
- [Cielo Pix API](https://apis.io/apis/cielo/cielo-pix-api/) — Cielo Pix API exposes the Brazilian Central Bank's instant-payment rails on a Cielo-hosted endpoint. It implements OAuth 2.0 Client Credentials with…
- [Cielo Payment Link API](https://apis.io/apis/cielo/cielo-payment-link-api/) — The Cielo Payment Link API lets merchants generate short, shareable payment URLs for sale on social media, WhatsApp, SMS, or email without a full…
- [Cielo Checkout API](https://apis.io/apis/cielo/cielo-checkout-api/) — Cielo Checkout is a hosted payment-page solution that handles credit card, debit, Pix, and boleto flows end-to-end, including PCI scope reduction and…
- [Cielo Refunds API](https://apis.io/apis/cielo/cielo-refunds-api/) — The Cielo Refunds API processes single and batch refund requests against captured transactions. Authentication is OAuth 2.0 Client Credentials issued…
- [Cielo Chargeback API](https://apis.io/apis/cielo/cielo-chargeback-api/) — The Cielo Chargeback API gives merchants programmatic access to dispute lifecycle management. It uses OAuth 2.0 Client Credentials plus mTLS against the…
- [Cielo Conciliador API](https://apis.io/apis/cielo/cielo-conciliador-api/) — The Cielo Conciliador API (powered by F360) provides programmatic access to financial reconciliation data including card installments, title installments,…
- [Cielo Promo API](https://apis.io/apis/cielo/cielo-promo-api/) — The Cielo Promo API lets partner platforms surface merchant promotions and discounts to cardholders. It uses an OAuth 2.0 authorization-code flow with…
- [Cielo LIO Remote Integration API](https://apis.io/apis/cielo/cielo-lio-remote-api/) — The Cielo LIO (now Cielo Smart) Remote Integration API lets ERP and commercial-automation systems drive payment operations on Cielo's Android POS terminals…
- [Cielo BIN Query API](https://apis.io/apis/cielo/cielo-bin-query-api/) — The Cielo BIN Query service returns metadata for a card BIN (Bank Identification Number) — issuing brand, card type, and additional rules — so e-commerce…
- [Cielo E-Wallets API](https://apis.io/apis/cielo/cielo-e-wallets-api/) — The Cielo E-Wallets API extends the e-Commerce API with support for digital-wallet payment methods, letting merchants accept Apple Pay, Google Pay, Samsung…
- [Cielo Tap on Phone](https://apis.io/apis/cielo/cielo-tap-on-phone/) — Cielo Tap on Phone (Cielo Tap) is the company's SoftPOS solution: it turns an NFC-capable smartphone into a card acceptance device with no separate…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Cielo Domain Security](https://apis.io/security/cielo/cielo-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Documentation](https://docs.cielo.com.br/)
- [Getting started](https://developercielo.github.io/tutorial/)
- [API reference](https://developercielo.github.io/manual/cielo-ecommerce)
- [Pricing](https://www.cielo.com.br/maquininha-cartao)
- [Support](https://atendimento.cielo.com.br/)
- [Blog](https://www.cielo.com.br/blog/)
- [Terms of service](https://www.cielo.com.br/termos-de-uso)
- [Privacy policy](https://www.cielo.com.br/politica-de-privacidade)
- [GitHub](https://github.com/DeveloperCielo)

## API Evangelist rating

**Unrated** — no public website could be reached for this company, so there was almost nothing to measure and nothing a reader could check.

This is not a score of zero. No rating is published for this company. If that is wrong because something public exists that we missed, say so on this repository or email [info@apievangelist.com](mailto:info@apievangelist.com) and it will be re-run — free, and no justification needed.

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cielo: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cielo/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
