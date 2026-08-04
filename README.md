# Footprint Analytics

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

Footprint Analytics is a blockchain data analytics platform providing unified REST and SQL APIs for querying DeFi protocol metrics, NFT market data, token analytics, GameFi economics, and on-chain activity across 30+ chains.

## Overview

- **Website**: https://www.footprint.network/
- **Documentation**: https://docs.footprint.network/docs/get-started
- **GitHub**: https://github.com/footprintanalytics
- **API Reference**: https://fp-api.readme.io/

## Data Coverage

- 30+ blockchain networks (Ethereum, Bitcoin, Solana, BNB Chain, Polygon, Arbitrum, Optimism, Sui, Starknet, and more)
- 30,000+ DeFi protocols
- 100M+ tokens
- 2M+ NFT collections
- 3,000+ blockchain games
- 400M+ wallet addresses

## API Categories

- **NFT**: Collection floor prices, sales volume, ownership, transfer history, metadata, wash trade filtering
- **DeFi**: TVL, DEX pool liquidity, protocol metrics, lending rates, options transactions
- **GameFi**: Game economics, player metrics, token flows, in-game asset data
- **Token Analytics**: Cross-chain token prices, market cap, holder distribution
- **Wallet**: On-chain activity profiles, cross-chain holdings

## Authentication

API key authentication. Register for a free API key at:
https://docs.footprint.network/reference/how-to-get-api-key

## Plans

| Plan | Price | Rate Limit |
|------|-------|------------|
| Free | $0/mo | ~30 req/min |
| Pro | Contact | ~300 req/min |
| Enterprise | Custom | Custom |

## Repository Structure

```
footprint/
  apis.yml              # APIs.json 0.19 provider profile
  plans/
    plans.yml           # Pricing plan details
  rate-limits/
    rate-limits.yml     # Rate limiting policies
  finops/
    finops.yml          # FinOps cost optimization guidance
  README.md
```

## Resources

- [Get Started](https://docs.footprint.network/docs/get-started)
- [API Key Registration](https://docs.footprint.network/reference/how-to-get-api-key)
- [GitHub Organization](https://github.com/footprintanalytics)
- [Medium Blog](https://medium.com/@footprintofficial)
- [QuickNode Integration](https://www.quicknode.com/builders-guide/tools/data-api-by-footprint-analytics)
