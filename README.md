# BigONE

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

BigONE is a cryptocurrency exchange (big.one) offering spot trading, contract (perpetual futures) trading, instant convert (flash swap) and wallet services. Its developer program at open.big.one documents four REST APIs on api.big.one (Spot v3, Wallet v3, Convert sapi v1 and Contract v2), JWT (HS256) authentication, and WebSocket streams, and publishes the OpenAPI definitions in the bigone-eng/openapi-specs GitHub repository and the WebSocket protobuf in bigone-eng/websocket-proto.

**Areas:** Company · Cryptocurrency · Exchange · Trading · Derivatives · Wallets · Market Data

## BigONE on APIs.io

Everything profiled for BigONE is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/bigone/](https://apis.io/providers/bigone/)** — or go straight to one of the APIs or properties below.

### APIs (16)

- [BigONE WebSocket API](https://apis.io/apis/bigone/bigone-websocket-api/) — Real-time spot market data and private order/account streams at wss://api.big.one/ws/v2 (JSON or protobuf messages, defined in the published…
- [BigONE Account API](https://apis.io/apis/bigone/bigone-account-api/) — Account Balance
- [BigONE Asset API](https://apis.io/apis/bigone/bigone-asset-api/) — Wallet Assets
- [BigONE Assets API](https://apis.io/apis/bigone/bigone-assets-api/) — Asset information
- [BigONE Deposit API](https://apis.io/apis/bigone/bigone-deposit-api/) — Wallet Deposits
- [BigONE Funding Account API](https://apis.io/apis/bigone/bigone-funding-account-api/) — Funding Account Balances
- [BigONE Market Data API](https://apis.io/apis/bigone/bigone-market-data-api/) — Public Market Data
- [BigONE Order API](https://apis.io/apis/bigone/bigone-order-api/) — Order Management
- [BigONE Ping API](https://apis.io/apis/bigone/bigone-ping-api/) — The Ping API from BigONE — 1 operation(s) for ping.
- [BigONE Position API](https://apis.io/apis/bigone/bigone-position-api/) — Position Management
- [BigONE Quote API](https://apis.io/apis/bigone/bigone-quote-api/) — Get quotes for conversion
- [BigONE Ranges API](https://apis.io/apis/bigone/bigone-ranges-api/) — Trading range limits
- [BigONE Trade API](https://apis.io/apis/bigone/bigone-trade-api/) — Trade History
- [BigONE Trades API](https://apis.io/apis/bigone/bigone-trades-api/) — Execute and manage trades
- [BigONE Transfer API](https://apis.io/apis/bigone/bigone-transfer-api/) — Wallet Transfers
- [BigONE Withdrawal API](https://apis.io/apis/bigone/bigone-withdrawal-api/) — Wallet Withdrawals

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [bigone-mcp.yml](https://apis.io/servers/bigone/bigone-mcp-yml/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Bigone Agentic Access](https://apis.io/agentic-access/bigone/bigone-agentic-access/)

#### JSON Schema (22)

The data models the API reads and writes.

- [Account](https://apis.io/schemas/bigone/bigone-account/)
- [Asset](https://apis.io/schemas/bigone/bigone-asset/)
- [AssetPair](https://apis.io/schemas/bigone/bigone-asset-pair/)
- [Candle](https://apis.io/schemas/bigone/bigone-candle/)
- [ConvertAsset](https://apis.io/schemas/bigone/bigone-convert-asset/)
- [ConvertQuote](https://apis.io/schemas/bigone/bigone-convert-quote/)
- [ConvertRange](https://apis.io/schemas/bigone/bigone-convert-range/)
- [ConvertTrade](https://apis.io/schemas/bigone/bigone-convert-trade/)
- [CreateOrderBody](https://apis.io/schemas/bigone/bigone-create-order-body/)
- [CreateTradeRequest](https://apis.io/schemas/bigone/bigone-create-trade-request/)
- [CreateTransferBody](https://apis.io/schemas/bigone/bigone-create-transfer-body/)
- [CreateWithdrawalBody](https://apis.io/schemas/bigone/bigone-create-withdrawal-body/)
- [Deposit](https://apis.io/schemas/bigone/bigone-deposit/)
- [Instrument](https://apis.io/schemas/bigone/bigone-instrument/)
- [Order](https://apis.io/schemas/bigone/bigone-order/)
- [PlaceOrderRequest](https://apis.io/schemas/bigone/bigone-place-order-request/)
- [Position](https://apis.io/schemas/bigone/bigone-position/)
- [Ticker](https://apis.io/schemas/bigone/bigone-ticker/)
- [Trade](https://apis.io/schemas/bigone/bigone-trade/)
- [TransferInfo](https://apis.io/schemas/bigone/bigone-transfer-info/)
- [UserTrade](https://apis.io/schemas/bigone/bigone-user-trade/)
- [Withdrawal](https://apis.io/schemas/bigone/bigone-withdrawal/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Bigone Context](https://apis.io/jsonld/bigone/bigone-context/)

#### Overlays (5)

OpenAPI overlays, including conversational phrasing for each operation.

- [Bigone Contract Overlay](https://apis.io/overlays/bigone/bigone-contract-overlay/)
- [Bigone Convert Overlay](https://apis.io/overlays/bigone/bigone-convert-overlay/)
- [Bigone Server Overlay](https://apis.io/overlays/bigone/bigone-server-overlay/)
- [Bigone Spot Overlay](https://apis.io/overlays/bigone/bigone-spot-overlay/)
- [Bigone Wallet Overlay](https://apis.io/overlays/bigone/bigone-wallet-overlay/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [BigONE API Rules](https://apis.io/rules/bigone/bigone-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Bigone Authentication](https://apis.io/security/bigone/bigone-authentication/)
- [Bigone Domain Security](https://apis.io/security/bigone/bigone-domain-security/)

#### Rate limits (1)

Published request limits.

- [Bigone Rate Limits](https://apis.io/rate-limits/bigone/bigone-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://big.one)
- [Documentation](https://open.big.one/docs/)
- [Getting started](https://open.big.one/docs/getting-started)
- [Support](https://t.me/bigapi)
- [GitHub](https://github.com/bigone-eng)

## API Evangelist rating

**Kin Score 40.7** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 62.2 |
| Contract governance | 22.0 |
| Operational transparency | 42.1 |
| Developer ergonomics | 56.5 |
| Access clarity | 0.0 |

**Agent readiness 38.9** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | verified |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | documented (partial credit) |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 15.7** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/bigone/](https://apis.io/providers/bigone/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for BigONE: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/bigone/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
