<h1 align="center">Nikita Beznosikov</h1>

<p align="center">
  <b>Senior Full-Stack / Product Engineer</b> · Payments · Checkout · Revenue-Critical Systems<br/>
  9+ years building e-commerce, analytics, fraud, and product platforms · Remote from Madrid
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/nikita-beznosikov/">
    <img src="https://img.shields.io/badge/LinkedIn-nikita--beznosikov-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://nikbeznosikov.github.io">
    <img src="https://img.shields.io/badge/Portfolio-nikbeznosikov.github.io-24292f?style=flat-square" alt="Portfolio"/>
  </a>
  <img src="https://img.shields.io/badge/Madrid-B2B%20%2F%20EOR%20ready-2ea043?style=flat-square" alt="Location"/>
</p>

---

### About

Senior Full-Stack / Product Engineer with **9+ years** building revenue-critical web systems across e-commerce, payments, checkout, fraud prevention, analytics, and experimentation.

Most of my recent work has focused on designing and operating the core commerce platform for a US-based DTC business that reached **~$1M/month revenue**, **1,000+ orders/day**, and **~80–90% mobile traffic**.

Core areas:

- Checkout and offer-management systems for dynamic funnels, upsells, cross-sells, and campaign experiments
- Multi-provider payment routing across Stripe, Braintree, PayPal, Apple Pay, and Google Pay
- Retry/fallback logic that recovered roughly **10–20% of initially failed transactions**
- Fraud prevention workflows, rule engines, IP blocking, and Visa CDRN chargeback automation
- Server-side tracking and attribution pipelines across Facebook CAPI, Google Ads, GTM, and BigQuery
- Internal tooling that lets non-engineering teams configure offers, landing pages, checkout flows, and experiments without code changes
- Platform modernization from PHP/Laravel to Next.js + Node.js + MongoDB, reducing new-offer launch time from **~2 weeks to ~2 days**

I am strongest in product environments where engineering work directly affects revenue, conversion, payment reliability, attribution quality, and operational efficiency.

---

### Selected work — public demos

Each repo isolates one production-grade concern and shows the kind of systems work I focus on: reliability, data flow, failure handling, security, performance, and product impact.

| Project | What it shows | Live | Stack |
| --- | --- | --- | --- |
| **[payment-system-demo](https://github.com/nikbeznosikov/payment-system-demo)** | Multi-provider checkout, retry with backoff + jitter, provider fallback, idempotency cache, Stripe webhook verification, live SSE event log | [demo](https://web-production-dcad7.up.railway.app/) | Node · TypeScript · Express · Postgres · Stripe |
| **[backend-architecture-template](https://github.com/nikbeznosikov/backend-architecture-template)** | Layered API, JWT auth with refresh-token rotation + reuse detection, transactional orders under `Serializable`, Zod-generated OpenAPI | [demo](https://backend-architecture-template-production.up.railway.app) · [Swagger](https://backend-architecture-template-production.up.railway.app/docs) | Node · TypeScript · Express · Prisma · Postgres |
| **[analytics-dashboard-demo](https://github.com/nikbeznosikov/analytics-dashboard-demo)** | 50k synthetic orders, downsampled time-series charting, virtualized server-side filtered table, KPIs with period-over-period deltas | [demo](https://analytics-dashboard-demo-khaki.vercel.app) | Next.js · React · TanStack · Recharts |
| **[ai-feature-demo](https://github.com/nikbeznosikov/ai-feature-demo)** | Bounded LLM call returning Zod-validated structured sentiment, Cloudflare Turnstile to protect cost surface | [demo](https://ai-feature-demo.vercel.app/) | Next.js · Gemini · Zod · Turnstile |

---

### Also building

- **[PassportPro](https://passportpro.app)** — Shopify app for EU Digital Product Passport / GPSR compliance. QR passports, bulk editing, AI autofill.
- **[GMC Store Readiness Scanner](https://apps.shopify.com/gmc-store-readiness-scanner)** — Shopify audit tool for Google Merchant Center compliance.
- **[CreditReel](https://creditreel.to)** — Pay-per-use video testimonial SaaS for collecting text and video reviews.

---

### Experience

**Senior Full-Stack / Product Engineer · Launchify Ventures**  
*2020 – Present · Remote / US-based product environment*

Owned and evolved revenue-critical commerce systems for a DTC e-commerce business reaching **~$1M/month revenue**, **1,000+ orders/day**, and **~80–90% mobile traffic**.

- Re-architected a PHP/Laravel monolith into a modular Next.js + Node.js + MongoDB commerce platform, reducing new-offer launch time from **~2 weeks to ~2 days**
- Designed the checkout and offer-management platform powering dynamic funnels, upsells, cross-sells, and **10–30 monthly A/B tests**
- Built multi-provider payment routing across Stripe, Braintree, PayPal, Apple Pay, and Google Pay, including retry and fallback logic
- Implemented fraud prevention workflows including rule-based risk checks, IP blocking, and automated Visa CDRN chargeback handling
- Built server-side tracking and attribution pipelines across Facebook CAPI, Google Ads, GTM consent flows, and BigQuery
- Developed internal platform tooling that allowed non-engineering teams to configure offers, landing pages, checkout flows, and campaign experiments without code changes
- Reduced video infrastructure cost by **~99%** by migrating media delivery from AWS S3 to Cloudflare Stream
- Improved mobile checkout performance and Core Web Vitals across mobile-heavy traffic

**Frontend Engineer · Sinlao Media**  
*2019 – 2020*

- Built React + Redux analytics dashboard used for media-buying decisions
- Developed real-time data visualizations and campaign performance views
- Improved frontend workflows for marketing users making optimization decisions

**Frontend Engineer · IQ Option**  
*2016 – 2019*

- Built real-time monitoring interfaces in React + WebSockets for high-frequency fintech data streams
- Optimized rendering performance for sustained real-time updates and data-heavy UI states
- Developed frontend components for operational dashboards where latency, clarity, and reliability were critical

---

### Stack

**Frontend**  
React · Next.js · TypeScript · JavaScript · Tailwind · React Native

**Backend**  
Node.js · Express · GraphQL · REST APIs

**Databases**  
MongoDB · PostgreSQL · Prisma

**Infrastructure**  
Cloudflare Workers · Cloudflare Stream · AWS · DigitalOcean · Vercel · Railway

**Payments**  
Stripe · Braintree · PayPal · Apple Pay · Google Pay · Visa CDRN

**Analytics**  
BigQuery · Facebook CAPI · Google Ads · GTM · Google Analytics API

**Testing**  
Vitest · Playwright · Cypress

---

<sub>
Looking for senior full-stack / product engineering roles at e-commerce platforms, Shopify ecosystem companies, payments-adjacent products, growth teams, or backend-heavy full-stack teams. Remote EU, B2B contract, or EOR. Reach me on <a href="https://www.linkedin.com/in/nikita-beznosikov/">LinkedIn</a>.
</sub>
