# Base

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

Base is Coinbase's Ethereum Layer 2 network built on the OP Stack and part of the Optimism Superchain. It exposes a standard Ethereum JSON-RPC interface for smart contracts and dApps, plus higher-level developer surfaces including Base Account (Smart Wallet, Sub Accounts, passkeys, paymaster-sponsored transactions), OnchainKit React components, Mini Apps, the canonical Bridge to Ethereum, and a Solana cross- chain bridge. Block exploration is available through BaseScan and Blockscout.

**Areas:** Layer 2 · Ethereum · OP Stack · Superchain · JSON-RPC · Smart Wallet · Bridge · Base

## Base on APIs.io

Everything profiled for Base is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/base-l2/](https://apis.io/providers/base-l2/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [Base Mainnet JSON-RPC](https://apis.io/apis/base-l2/mainnet-rpc/) — Standard Ethereum JSON-RPC endpoint for Base Mainnet (chain ID 8453). Supports eth_*, net_*, web3_*, and Optimism-specific extensions for fee estimation and…
- [Base Sepolia JSON-RPC](https://apis.io/apis/base-l2/sepolia-rpc/) — Public JSON-RPC endpoint for the Base Sepolia testnet (chain ID 84532) used for development, contract deployment, and integration testing.
- [Base Flashblocks RPC](https://apis.io/apis/base-l2/flashblocks-rpc/) — Pre-confirmation JSON-RPC endpoint exposing Flashblocks — sub-block streams of ordered transactions that allow apps to react to pending state with…
- [Base Bridge](https://apis.io/apis/base-l2/bridge/) — Canonical cross-chain bridge between Ethereum L1 and Base L2 for depositing and withdrawing ETH and ERC-20 tokens, secured by the OP Stack bridge contracts.
- [Base / Solana Bridge](https://apis.io/apis/base-l2/solana-bridge/) — Cross-chain bridge enabling asset transfers between Base and Solana, integrated into the Base ecosystem app surface.
- [Base Account / Smart Wallet](https://apis.io/apis/base-l2/account/) — Base Account (formerly Coinbase Smart Wallet) is an ERC-4337 smart contract wallet with passkey sign-in, sub-accounts, session keys, sponsored transactions…
- [OnchainKit](https://apis.io/apis/base-l2/onchainkit/) — React component library and TypeScript SDK (@coinbase/onchainkit) for building onchain apps on Base — wallet, identity, transaction, swap, checkout, fund,…
- [BaseScan Block Explorer](https://apis.io/apis/base-l2/basescan-explorer/) — Etherscan-family block explorer for Base Mainnet and Sepolia with a public contract / transaction / address API.
- [Base Blockscout Block Explorer](https://apis.io/apis/base-l2/blockscout-explorer/) — Blockscout-powered open-source block explorer for Base with REST and GraphQL APIs.
- [Base JSON-RPC API](https://apis.io/apis/base-l2/base-l2-json-rpc-api/) — Ethereum JSON-RPC 2.0 endpoint

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### GraphQL (1)

GraphQL schemas.

- [Moved to /providers/base-l2/](https://apis.io/graphqls/base-l2/base-l2-graphql/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [base-l2](https://apis.io/servers/base-l2/base-l2/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Base L2 Agentic Access](https://apis.io/agentic-access/base-l2/base-l2-agentic-access/)

#### Collections (2)

Postman and Open Collection request collections.

- [Base JSON-RPC API](https://apis.io/collections/base-l2/open-base-l2/)
- [Base JSON-RPC API](https://apis.io/collections/base-l2/open-base-l2-json-rpc-api/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Base L2 Domain Security](https://apis.io/security/base-l2/base-l2-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Base L2 Plans Pricing](https://apis.io/plans/base-l2/base-l2-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Base L2 Rate Limits](https://apis.io/rate-limits/base-l2/base-l2-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Base L2 Finops](https://apis.io/finops/base-l2/base-l2-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.base.org)
- [Documentation](https://docs.base.org)
- [Blog](https://base.mirror.xyz)
- [GitHub](https://github.com/base)

## API Evangelist rating

**Kin Score 23.9** — emerging · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 49.6 |
| Contract governance | 0.0 |
| Operational transparency | 23.7 |
| Developer ergonomics | 14.3 |
| Access clarity | 5.3 |

**Agent readiness 29.0** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 5.4** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/base-l2/](https://apis.io/providers/base-l2/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Base: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/base-l2/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
