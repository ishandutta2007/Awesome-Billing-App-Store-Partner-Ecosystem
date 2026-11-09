# Awesome-Billing-App-Store-Partner-Ecosystem

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.



I also have to flag what the search results actually support, because **the fee models changed dramatically in 2026**, and **the open-source side is a marketplace engine, not an app store ecosystem**.



## The data problems



**Xero retired revenue share entirely on March 2, 2026.** The old model (Xero App Store Subscriptions and Commercial Billing) is gone. The new model is five tiers: **Starter (free, 5 connections), Core ($35 AUD/mo, 50 connections, 10 GB egress), Plus ($245 AUD/mo, 1,000 connections, 50 GB), Advanced ($1,445 AUD/mo, 10,000 connections, 250 GB), Enterprise (quote)**. **App Store listing is not available on Starter or Core—it starts at Plus** . Egress overage is **$2.40 AUD/GB**. Do not cite the old revenue share model.



**QuickBooks App Store listing is free, but revenue share applies to referred subscriptions.** Developer registration is free; there is no per-API-call charge. Apps that monetize through the store pay Intuit a revenue share on referred end-customer subscriptions, **negotiated per app** . One Intuit forum answer from 2020 says "we do not charge any fee" —but that is six years old and conflicts with the current API pricing page's "revenue share" language. **Cite the current negotiation language, not the 2020 forum post.**



**Make's Community Apps are 100% revenue to the partner, but only official partners can submit.** The program is in beta; only partners with a signed Partnership Agreement may submit. Partners license apps directly to users; **Make does not conduct technical review** . **You keep 100% of revenue** as of today . This is the most generous fee model in the results—but the partner-only gate is a real barrier.



**Chargebee's partner program has no membership fee.** It covers ISV, Solution, and Reseller partners; referral commissions, reseller margin, and deal registration via partner portal . **No fee figures or revenue share percentages were surfaced.**



**No pricing surfaced for:** Stripe App Marketplace, Shopify App Store, Salesforce AppExchange, HubSpot App Marketplace, Zapier App Directory, or Zendesk Marketplace in these results.



## Open-source: what actually exists



**Mercur** is the only open-source marketplace platform surfaced: **built on MedusaJS**, with vendor portal, admin panel, block-based architecture, CLI, and full code ownership. It is **"the first truly limitless open source marketplace platform"** with **no transaction fees or vendor lock-in** .



**Mercur is a multi-vendor commerce marketplace engine, not an app store ecosystem.** It handles vendors, commissions, and storefronts for products—it does not provide app packaging, developer SDKs, or an extension review pipeline. **Do not present it as a replacement for Chargebee's or Stripe's app marketplace.**



**Nextcloud launched an ISV partner program in July 2026** to grow its App Store from 600 to 6,000 apps, with the contract between developer and customer and the developer responsible for support . This is a real app store ecosystem, but it is Nextcloud-specific—not a generic platform.



## What I recommend



**Split into two honest categories:**



**1. SaaS App Marketplaces & Partner Ecosystems** (proprietary, fee models vary wildly):

- **Xero App Store** — five tiers, listing starts at **Plus $245 AUD/mo**, egress $2.40/GB 

- **QuickBooks App Store** — free listing; revenue share on referred subscriptions, **negotiated per app** 

- **Make Apps** — **100% revenue to partner**, partner-only, no technical review 

- **Chargebee** — no membership fee; ISV/Solution/Reseller tracks 

- **Stripe, Shopify, Salesforce, HubSpot, Zapier, Zendesk** — **fee data not surfaced**



**2. Open-Source Marketplace Infrastructure:**

- **Mercur** — MedusaJS-based multi-vendor marketplace engine, no transaction fees 

- **Nextcloud App Store** — ISV program, developer-owned contracts 



**Flag the Xero change explicitly:** the revenue share model is dead; you now pay a flat monthly fee plus egress overage, and **listing requires Plus tier or higher** . This is a fundamental shift from percentage-of-revenue to infrastructure-style pricing.



If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not cite Xero's retired revenue share model, present Make's partner-only program as open to all, or claim Mercur replaces a commercial app marketplace.
