# Awesome-Media-Advertising-Subscriber-CRM

# Top Media Advertising & Subscriber CRM Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Ad Sales Management, Subscription Lifecycle & Audience Monetization*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Media Advertising & Subscriber CRM Tools**. These tools help publishers, broadcasters, and media companies manage advertising sales pipelines, subscriber acquisition and retention, campaign trafficking, billing reconciliation, and audience monetization across digital, print, TV, and streaming channels.

**Examples** include Salesforce Media Cloud, WideOrbit, Operative, Lineup Systems, Naviga, Mediaocean, Matrix Solutions, Mirada Media, Plannet Media, and ADmantX (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom ad serving, subscription billing, and transparent audience data — ideal for independent publishers, broadcasters, and developers building data-sovereign media CRM platforms.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Media Cloud](https://www.salesforce.com/media/)**  
  Purpose-built media CRM with advertising sales management, subscriber lifecycle tools, and audience segmentation for publishers and broadcasters.

- **[WideOrbit](https://www.wideorbit.com/)**  
  Unified ad sales and broadcast management platform spanning proposal management, traffic scheduling, billing, and revenue analytics across linear TV, radio, and digital channels [citation:6]. The platform is designed for broadcasters, networks, and digital media enterprises with API-first architecture for CRM and ERP integrations.

- **[Operative](https://www.operative.com/)**  
  Advertising business management platform for media companies with order management, revenue analytics, and CRM capabilities.

- **[Lineup Systems](https://www.lineup.com/)**  
  Advertising and subscription management platform for media companies with CRM and revenue operations.

- **[Naviga](https://www.navigaglobal.com/)**  
  Media industry software for publishers with CRM, advertising, subscription management, and content operations.

- **[Mediaocean](https://www.mediaocean.com/)**  
  Advertising workflow automation and media management infrastructure connecting brands, agencies, and media sellers.

- **[Matrix Solutions](https://www.matrixsolutions.com/)**  
  Media CRM and sales intelligence platform connecting advertisers, agencies, and media sellers with unified data.

- **[Mirada Media](https://www.mirada.tv/)**  
  Media management and CRM solutions for broadcasters and content distributors.

- **[Plannet Media](https://www.plannetmedia.com/)**  
  Media planning and CRM software for advertising agencies and media buyers.

- **[ADmantX](https://www.admantx.com/)**  
  Semantic advertising intelligence platform for contextual targeting, brand safety, and audience insights.

## Open-Source GitHub Projects

- **[Revive Adserver](https://github.com/revive-adserver/revive-adserver)**  
  Leading open-source ad serving platform enabling publishers, ad networks, and advertisers to serve ads on websites, apps, and video players with detailed impression, click, and conversion tracking [citation:13][citation:16]. Features banner management interface, zone-based ad selection, campaign targeting, ad capping, and VAST2 video ads support. GPL licensed [citation:14][citation:18].

- **[Open Ad Server](https://github.com/ediboko1980/openadserver)**  
  Self-hosted ad serving platform with ML-powered CTR prediction (DeepFM, LR, FM models), OpenRTB-compatible architecture, and real-time bidding roadmap [citation:1][citation:4]. Includes campaign/creative/advertiser CRUD APIs, impression/click/conversion tracking, and Prometheus metrics for observability. Python/FastAPI/PyTorch stack [citation:9].

- **[Lago](https://github.com/getlago/lago)**  
  Open-source usage-based billing and subscription management platform, positioned as an alternative to Stripe Billing and Chargebee [citation:10]. Send usage events via API; Lago meters them, applies plans and taxes, and issues PDF invoices. Supports subscriptions, credits, hybrid pricing, and payment provider integrations (Stripe, Adyen, GoCardless) [citation:10].

- **[BillaBear](https://github.com/billabear/billabear)**  
  Open-source subscription management and billing system with Stripe integration, tax management (EU VAT, VAT Sense), workflows for async tasks, and multi-currency/multi-language support [citation:8]. Includes subscription reports (LTV, churn), dunning, vouchers, credit notes, and customer-facing frontend via Stripe.js [citation:8].

- **[Autumn](https://github.com/useautumn/autumn)**  
  Open-source pricing and billing layer between Stripe and applications, supporting subscriptions, credit systems, usage-based models, and custom plans [citation:5]. Provides three core functions (`/attach`, `/check`, `/track`) for embedding billing logic with minimal code [citation:5].

- **[Meteroid](https://github.com/meteroid-oss/meteroid)**  
  Open-source billing and subscription management platform built in Rust for high-performance usage event processing [citation:12]. Supports subscription billing, usage-based pricing, hybrid models, invoicing with tax compliance, coupons, trials, and revenue analytics. API-first architecture [citation:12].

- **[Mautic](https://github.com/mautic/mautic)**  
  Open-source marketing automation platform with lead management, campaign builder, and email marketing. Suitable for media organizations managing advertiser relationships and audience engagement.

- **[EspoCRM](https://github.com/espocrm/espocrm)**  
  Open-source CRM with customizable entities, workflow automation, and email integration. Adaptable for media organizations managing advertiser relationships and subscription data.

- **[SuiteCRM](https://github.com/salesagility/SuiteCRM)**  
  Open-source CRM fork of SugarCRM with modules for sales, marketing, and support. Can be customized for media industry use cases including advertising sales tracking.

- **[Twenty](https://github.com/twentyhq/twenty)**  
  Modern open-source CRM with contacts, companies, and opportunities management for advertiser and subscriber relationships.

### Additional Strong Open-Source Options

- **[JustSubs](https://github.com/ridho/justsubs)** — Self-hosted Laravel subscription and billing infrastructure with polymorphic subscribers, built-in dashboard, and agnostic payment drivers [citation:17].
- **[Open Payment Host](https://github.com/abishekmuthian/open-payment-host)** — Self-hosted payment and subscription host supporting Stripe, Square, PayPal, and Razorpay with webhook integration [citation:19].
- **[django-subscription-midtrans](https://github.com/rissets/django-subscription-midtrans)** — Django subscription management with Midtrans payment gateway integration, recurring billing, and Celery-based async processing [citation:2].
- **Audience Analytics** — Matomo, Plausible, and Umami for privacy-focused media audience measurement.
- **Email Marketing** — Listmonk, phpList, and Keila for subscriber communications and newsletters.

**Frameworks for building custom systems**: Combine **Revive Adserver** for ad serving, **Lago** or **BillaBear** for subscription billing, **Mautic** for audience engagement, and **Matomo + Metabase** for media analytics to build a complete self-hosted media CRM stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Media CRM tools must comply with data protection regulations (GDPR, CCPA), advertising standards, and content licensing requirements.
- Self-hosted open-source solutions require proper security hardening, scalability planning, and technical expertise for maintenance.

---

**Made for media executives, advertising sales teams, subscription managers, and developers building media-focused CRM platforms.**  
Let's make media advertising and subscriber CRM more open, data-sovereign, and publisher-friendly.
