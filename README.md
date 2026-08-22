# Crossmint (crossmint)

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

Crossmint is a Web3 platform offering APIs for wallets, NFT minting, checkout, payments, embedded checkout, and verifiable credentials. Supports server-managed wallets across EVM and Solana, fiat-on-ramp checkout, and credit-card-funded NFT purchases.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/crossmint/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/crossmint/refs/heads/main/apis.yml)

## Tags

- Web3
- Wallets
- NFT
- Payments
- Checkout

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Crossmint Wallets API

REST API to create and manage server-side custodial and non-custodial smart wallets across EVM and Solana, sign transactions, manage delegated permissions.

- **Human URL:** [https://docs.crossmint.com/wallets/introduction](https://docs.crossmint.com/wallets/introduction)
- **Base URL:** `https://staging.crossmint.com/api/2022-06-09 (staging) | https://www.crossmint.com/api/2022-06-09 (prod)`

#### Tags

- REST
- Wallets
- Smart Wallets

#### Properties

- [Documentation](https://docs.crossmint.com/wallets/introduction)
- [Postman Collection](collections/crossmint.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/crossmint.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Crossmint Minting API

REST API to mint and manage NFTs on multiple chains, including collection creation, batch minting, and metadata management.

- **Human URL:** [https://docs.crossmint.com/minting/introduction](https://docs.crossmint.com/minting/introduction)
- **Base URL:** `https://www.crossmint.com/api/2022-06-09`

#### Tags

- REST
- NFT
- Minting

#### Properties

- [Documentation](https://docs.crossmint.com/minting/introduction)
- [Postman Collection](collections/crossmint.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/crossmint.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Crossmint Checkout API

REST API for hosted and headless checkout flows allowing credit-card and crypto purchases of NFTs.

- **Human URL:** [https://docs.crossmint.com/payments/introduction](https://docs.crossmint.com/payments/introduction)
- **Base URL:** `https://www.crossmint.com/api/2022-06-09`

#### Tags

- REST
- Checkout
- Payments

#### Properties

- [Documentation](https://docs.crossmint.com/payments/introduction)
- [Postman Collection](collections/crossmint.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/crossmint.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Crossmint Verifiable Credentials API

REST API to issue, manage, and verify verifiable credentials anchored on chain.

- **Human URL:** [https://docs.crossmint.com/verifiable-credentials/introduction](https://docs.crossmint.com/verifiable-credentials/introduction)
- **Base URL:** `https://www.crossmint.com/api/v1-alpha1/credentials`

#### Tags

- REST
- Credentials
- VC

#### Properties

- [Documentation](https://docs.crossmint.com/verifiable-credentials/introduction)
- [Postman Collection](collections/crossmint.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/crossmint.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Crossmint Headless Checkout (Order API)

REST Order API for fully headless on-chain commerce flows including fiat and crypto payment intents.

- **Human URL:** [https://docs.crossmint.com/payments/headless/overview](https://docs.crossmint.com/payments/headless/overview)
- **Base URL:** `https://www.crossmint.com/api/2022-06-09/orders`

#### Tags

- REST
- Order

#### Properties

- [Documentation](https://docs.crossmint.com/payments/headless/overview)
- [Postman Collection](collections/crossmint.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/crossmint.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/crossmint)
- [LinkedIn](https://www.linkedin.com/company/crossmint-io)
- [Website](https://www.crossmint.com/)
- [Plans](plans/crossmint-plans-pricing.yml)
- [Rate Limits](rate-limits/crossmint-rate-limits.yml)
- [Fin Ops](finops/crossmint-finops.yml)
- [L L Ms Txt](https://docs.crossmint.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
