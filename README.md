# Awesome Billing & App Store Partner Ecosystem

A curated list and analytical guide to billing platforms, app store ecosystems, partner marketplaces, and multi-vendor monetization infrastructure.

---

## Sector Overview & Market Dynamics

The global subscription billing and recurring management market is estimated between **$7.2 billion and $8.3 billion**, projected to expand at a **CAGR of 11% to 15%** past **$20+ billion** over the next decade. Structurally, the ecosystem exhibits a dual dynamic: it is **moderately to highly fragmented** at the SME and boutique plugin level due to low barriers to basic invoicing tools, but **heavily concentrated** at the enterprise tier (oligopolistic / winner-take-most dynamics) where extreme platform switching costs, ERP/CRM compliance mandates (ASC 606/IFRS 15), and complex multi-currency usage billing entrench market leaders like Stripe, Intuit, Zuora, and Chargebee.

---

## SaaS Products & Partner Ecosystems

The table below covers the primary billing, accounting, and automation SaaS platforms offering developer app stores and partner programs. Sorted by company scale (Valuation / Market Cap in descending order).

| SaaS Product | Size (Valuation / Revenue) | Starting Pricing Tier | Free Tier / Free Trial Limits | Partner & App Store Ecosystem Model |
| :--- | :--- | :--- | :--- | :--- |
| **Stripe** (Stripe Billing & App Marketplace) | **$159B Valuation** (2026 tender offer) / ~$6.8B net revenue | **$0/mo** + 0.7% of recurring billing volume (Pay-as-you-go); or **$620/mo** committed tier (covers up to $100k/mo volume) | **Free test mode forever** (unlimited API testing in sandbox); 0-day platform charge for sandbox; standard 30-day merchant trials supported with zero extra platform fee | Free registration for Stripe App Marketplace; apps embed directly into the Stripe Dashboard. |
| **QuickBooks** (Intuit Developer / App Store) | **~$93B Market Cap** / $21.45B annual revenue (FY26) | **$38/mo** (Simple Start tier, 1 user + 2 accounting firms) | **30-day free trial** with full feature access (or restricted $0/mo QuickBooks Free basic tracking plan) | Free developer portal registration with zero per-call charges; app store revenue share on referred subscriptions is negotiated per partner app. |
| **Make** (Celonis / Make Community Apps) | **$13B Valuation** (Parent Celonis) / ~$53M ARR | **$9/mo** (Core Plan billed annually; 10,000 ops/mo, unlimited scenarios) | **Free forever plan**: 1,000 operations/month, max 2 active scenarios, minimum 15-minute scheduling interval, 512 MB transfer | **100% revenue kept by the partner**; partner program requires a signed Partnership Agreement (beta, partner-only submission). |
| **Xero** (Xero App Store) | **~$11B Market Cap** / NZD $2.8B (~$1.7B USD) FY26 revenue | **$27/mo** (US Early Plan) / **A$37/mo** (AU Ignite Plan) | **30-day free trial** (unlimited access to core reconciliations and invoicing; no credit card required upfront) | Developer portal tiers: **Starter (Free, 5 connections)**, Core (A$35/mo, 50 connections). **App Store listing requires Plus tier (A$245/mo, 1,000 connections)** or Advanced (A$1,445/mo); egress overage A$2.40/GB. Flat-fee infrastructure model replaced rev-share. |
| **Chargebee** (Chargebee Partner Network) | **$3.5B Valuation** (Series H) / ~$250M ARR | **$0/mo** (Starter Plan until cumulative limit reached); or **$599/mo** (Performance tier) | **Free forever Starter Plan up to $250,000 in cumulative lifetime billing**; 0.75% overage fee applies on volume exceeding $250k | No partner membership fee; supports ISV, Solution, and Reseller partner tracks with referral commissions, reseller margins, and deal registration. |

---

## Open-Source Marketplace & App Store Infrastructure

For teams seeking self-hosted or open-source alternatives to commercial app store infrastructure:

* **[Mercur](https://github.com/mercurjs)** — An open-source multi-vendor marketplace engine built on MedusaJS. Features vendor portals, an admin dashboard, block-based modular architecture, CLI, and zero transaction fees. *(Note: Mercur is a commerce and product multi-vendor marketplace engine, not a developer app store package manager).*
* **[Nextcloud App Store & ISV Ecosystem](https://nextcloud.com)** — Self-hosted app ecosystem with an ISV partner program enabling developers to deploy directly to thousands of private cloud instances with direct developer-to-customer licensing.

---

## Contributing

Contributions, updates to partner fee schedules, and additions are welcome! Please open an issue or pull request.
